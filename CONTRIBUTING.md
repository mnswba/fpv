# Contributing

Thank you for helping improve this FPV drone platform. The most useful contributions are reproducible engineering observations: a measured improvement, a clearly described failure, a manufacturing correction, or a safe flight-test method.

## Before opening an issue

Search existing issues first. For a design or flight report, include:

- the repository commit or file revision;
- aircraft mass and major hardware revisions;
- motor, propeller, battery, ESC, and flight-controller details;
- material, printer, layer settings, post-processing, or machining notes;
- firmware version and relevant configuration changes;
- test location type, weather, battery state, and test duration;
- measured current, temperature, vibration, Blackbox findings, or photos;
- the smallest reproducible change and the result.

Never upload tokens, receiver identifiers, private addresses, personal information, or telemetry that identifies a person or location.

## CAD and manufacturing contributions

Describe units, coordinate system, revision, tolerances, intended material, and manufacturing process. For STL/3MF or other binary files, explain the change in the pull request and keep filenames stable unless a rename is necessary. Do not silently replace a known-good file; state what changed and why. Editable source CAD (STEP, F3D, etc.) is welcome alongside exported meshes.

Before proposing a flight-ready revision, do a dry fit and a no-propeller bench inspection: propeller clearance, motor-bell clearance, fastener retention, cable routing, battery restraint, cooling, and structural interference.

## Flight and tuning contributions

Use a clear, legal test area and follow the safety section in the README. Save the configuration backup (`diff all`) and keep the original Blackbox log. For PID or filter changes, make one parameter-family change per short test flight and report abort conditions.

## Pull requests

Explain:

1. what changed;
2. which revision or hardware it targets;
3. how it was validated;
4. what remains unverified;
5. any license or attribution implications.

By contributing, you confirm you have the right to submit the material and that it can be distributed under this repository's license ([`LICENSE.txt`](LICENSE.txt)).

## Safety and scope

This is experimental aircraft work. Remove propellers for configuration and bench work, use safe LiPo procedures, and stop after an impact, failsafe, abnormal sound, loss of control, or excessive temperature. Military, weapon, armed, or combat applications are out of scope.
