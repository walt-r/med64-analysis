# med64-analysis
Code for analyzing Margolis lab Med64 data

## Formatting of MED64 exported files for analysis  

### "units_ts.mat" file: ###   
* Unit.ts=listoftimestampsofactionpotentialsforthatunit,insec   
* Unit.mWave=themeanwaveformforthatUnit,displayedat20kHz(0.05usecbetween   
datapoints, or a total os 3 msec across the 60 pts)   

### "unit_electrode.csv" file: ###  
* two column file, first column is the electrode number, second column is the Unit number (same unit numbering as the .mat file).  
  
| electrode | unit |
| --- | --- |
| 19 | 1 |
| 20 | 2 |
| 20 | 3 |

### "treatments.csv" file: ###  
* three column file, start time (sec), end time (sec), treatment name
 
| begin | end | label |
--- | --- | ---
| 0 | 600 | baseline |
| 600 | 1200 | DAMGO |
| 1200 | 1800 | wash1 |

