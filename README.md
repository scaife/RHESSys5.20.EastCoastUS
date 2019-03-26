# RHESSys5.20.EastForest
Jan13 2019 version
- dynamic subsurface flow direction based on runtime water table elevation
- flowtable actionCodes
  - gw_flag & gwtoriparian_flag & actionRIPARIAN
  - gw_flag & actionGWDRAIN
  - grassIrrigation_flag & actionIRRIGRATION & landuse.def [max amount mm/day] (during growth season only; water stress adjustment)
  - fertilizer_flag & actionFERTILIZE & landuse.def [amount (kgN/m2/mo) and freq (30 days)] (during growth season only)
  - sewer_flag & actionSEWER
  - actionPIPEDRAIN 
- corrected cpool / npool dynamics in vegetation
- new metric to evaluate annual vegetation respout: GPP + cpool - Re 
- excessive cpool/npool goes to DOC/DON
- first version of SAT_solutes code implemention
- actionRiparian bug fixed
- sun angle and aspect angle fixed 
- tested in Coweeta WS18 diversed canopy and local averaged canopy models
