# Team VITAKSH — Avionics Recruitment

## VEGA-01 | Flight Systems Challenge

> **VEGA-01 is getting ready to fly. The payload is ready. The ground station isn't. And somewhere in the system, something is wrong.**

### The story

A small high-altitude balloon is being prepared for flight.

Inside VEGA-01 is a flight computer connected to sensors, GNSS, a radio, and the rest of the avionics stack. On the ground, the team needs a station that can tell them what the payload is doing without having to stare at a stream of raw numbers.

Something has been left unfinished.

The payload is producing data, but the ground team does not yet have a useful way to understand it. At the same time, one of the sensors still needs to be brought up and checked before it can become part of the system.

That is where you come in.

You are joining the avionics team during the build, not after everything has already been solved. The documentation is there. The tools are there. The problem is yours to figure out.

Welcome to VEGA-01.

These two practical missions are built around the same flight system. You will work with telemetry, ground systems, electronics, embedded software, and fault investigation.

This is not a theory exam. Documentation, datasheets, search, compilers, CAD tools, GitHub, and AI tools may be used. The important part is that you understand and can explain what you submit.

## Mission 01 — Wake the Ground Station

The payload is already sending telemetry.

The problem is that raw telemetry is not very useful to someone operating a balloon from the ground.

Your job is to turn that data into a ground-station view that lets an operator understand what is happening to VEGA-01.

→ [Open Mission 01](mission-01-ground-station/task.md)

## Mission 02 — Bring a Sensor to Life

The flight computer needs another environmental measurement.

A BMP280 pressure and temperature sensor has been selected, but it is not simply a matter of plugging it in and hoping for the best.

Your job is to work out how the sensor should be connected, how the controller communicates with it, and how to check that the measurements make sense.

You will need to find your way through a datasheet, a hardware interface, and a small amount of embedded code.

→ [Open Mission 02](mission-02-sensor/task.md)

## What we want to see

We do not expect you to know everything already.

You might get stuck. Your first attempt might fail. You might find something in a datasheet that does not make sense at first.

That's fine.

We are interested in how you:

**learn → build → test → break → debug → explain**

A simple solution that was tested and understood is more useful than a complicated solution that was copied and never checked.

We are also interested in the questions you ask, the assumptions you make, and what you do when your first idea turns out to be wrong.

## Suggested schedule

You have roughly **two weeks** for the complete challenge.

The missions themselves are small. Use the time to make a first attempt, test it, investigate anything unexpected, improve it, and document what you learned.

You do not need to spend the whole two weeks working on it.

## Submission

Keep your work under `submission/` and use the provided submission template.

There is no prize for making the repository look enormous.

Make it easy for another person on the team to open your work and understand what you did.

Good luck.

**— Team VITAKSH**
