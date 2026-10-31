# Power, audio and wiring observations

[Back to README](../README.md)

## Evidence boundary

These are owner-reported observations for one vehicle. There is no verified connector pinout or electrical schematic in this repository.

| Observation | What remains unknown |
| --- | --- |
| A purple wire was measured as switched power | Connector identity, cavity number, measured values, circuit capacity and protection |
| Original blue RTI connector is disconnected | Verified cavity functions and final reconnection arrangement |
| OEM mechanism and electronics are retained | Behavior after original RTI power is restored |
| A Y-splitter is planned | Exact connectors, circuit routing, ratings and compatibility |
| WEFA MELBUS Bluetooth audio is used with HU-850 | Exact adapter revision, pairing sequence and complete routing |
| Microphone / Siri likely works | Which microphone is active and repeatable end-to-end results |

## Power documentation required before replication

Record the exact connector and cavity identification, measurement reference point, measured voltage in each ignition state, donor input requirements, adapter used, and circuit protection. Verify the intended load against the identified circuit.

Do not infer a pin function from wire colour, connector colour, or a photograph. Do not treat the purple-wire observation as permission to connect the donor unit directly to it.

The Y-splitter is a pending part of this build, not a proven wiring solution. Confirm its purpose, pin mapping and ratings before connecting it, and document the final arrangement after testing.

## Audio path

The build uses a WEFA MELBUS Bluetooth adapter to provide audio through the original HU-850. CarPlay and Waze are reported working.

The precise pairing arrangement has not been captured in the accessible source. This repository therefore does not claim a particular phone-to-WEFA or VENBES-to-WEFA pairing sequence. Record the actual route, selected HU-850 source and any relevant device settings when verified.

## Microphone and Siri

Microphone / Siri operation is considered likely, not confirmed. A successful Siri test should establish which microphone receives speech, whether the request is recognized and whether the response is audible through the intended speakers. Call microphone performance is a separate test and remains undocumented.
