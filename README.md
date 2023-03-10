# PureData
PureData patches, created in PurrData

## Momentary Toggle Toggle
_mommentary-toggle-toggle.pd_

This 'graph-on-parent' patch came from the need to take MIDI button presses (momentary) and get toggle switch behavior (on/off), and to be able to switch between behaviours.

Inlet values are passed to the Outlet directly in 'Momentary' mode. In 'Toggle' mode, When the Toggle toggle is toggled, Zero is output if the same consecutive non-zero number is input twice. Otherwise you get the non-zero number.

<img src="/doc/mtt1.gif" width="250" /> <img src="/doc/mtt2.gif" width="250" /> <img src="/doc/mtt3.gif" width="250" />

*Inputs*: Value (float), External toggle (toggle)

*Outputs*: Value (float), External toggle colour message
