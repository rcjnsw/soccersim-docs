---
layout: page
title: Reference
parent: JavaScript
nav_order: 999
permalink: js/reference/
---

# Reference
This is a raw reference guide for functions available in the SoccerSim.

## Table of contents
1. Table of contents
{:toc}

## Robot
### setMotorSpeed

<div class="code-example" markdown="1">
`setMotorSpeed(motor, speed)`
Sets the motor speed, for a particular motor.
* `motor` (String) motor name, e.g. `'motorA'`
* `speed` (Number) number between -100 and 100, a positive value drives the motor forwards.
</div>

```javascript
// Spin the robot around
setMotorSpeed('motorA', 30);
setMotorSpeed('motorB', -30);
```

### stopMotor

<div class="code-example" markdown="1">
`stopMotor(motor)`
Stops a particular motor.
* `motor` (String) motor name, e.g. `'motorA'`
</div>

```javascript
// Stops both motors
stopMotor('motorA');
stopMotor('motorB');
```

### getMotorSpeed

<div class="code-example" markdown="1">
`getMotorSpeed(motor)`
Returns the current speed of the motor.
* `motor` (String) motor name, e.g. `'motorA'`
</div>

```javascript
if (getMotorSpeed('motorA') > 10) {
	// Speed is over 10
}
```


----

## Sensors
