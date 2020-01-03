# MVTX stave GDML model change log
- **mvtx\_stave\_v01.gdml**
Old model created by Darren from ALICE TDR. A lot of things have been changed after that!!!!

- **mvtx\_stave\_v02.gdml**
Updated Mvtx stave mechanical structure with ALICE model from O2 version of 04/04/2019
Hic model and chip orientation did not changed to keep compatibility with code in Cylinder\_geometry code

- **mvtx\_stave\_v1p0.gdml**
Latest ALICE IB HIC and ALPIDE chip models:
  + 50 um ALPIDE chip
    + 15 um Metal Stack, 30 um Active Volume and 5 um Subtrate

  + IB HIC
    + Latest FPC model with capacitors and resistor on top
    + 50 um of glue between FPC and chips

- **mvtx\_stave\_v1p1.gdml**
  - Fix some FPC Kapton width 125 um -> 75 um

- **mvtx\_stave\_v1p2.gdml**
  + Change negative rot to positive and round distances to nearest um.
  + New FPC model: unique Kapton solid with two Al volumes
  + Fix bug in the chip position of ALICE stave model. -> Chip must be centered to CP in X.
  + Sensor volume = Active volume (1.376256 x 2.994176), TODO -> change to whole chip
  + Using a box as container volumen for SF connectors (IBConnectorASide, IBConnectorCSide).
  Workaround for overlap issues seeing in geant4.10.5.p01

- **mvtx\_stave\_v1p21.gdml**
  + Rotate stave to have pipe and connectors pointing to negative Z axis (discusion with MIng 2020-01-02)
