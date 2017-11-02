# kde_viz_app
Small app to get some descriptive stats, produce 2-dimensional kernel density plots and save them to a local file.

# ToDoes

## Data upload
- handle different formats
  - txt
  - csv
  - xl
- customize the read.XX call
  - header flag
  - specify NA values
  
## Raw data
- look at the data
  - sort rows by columns
  
## Descriptives
- descriptive summary
  - NA count
  - min-max
  - mean, quantiles, ...
  
## Calculate KDE
- check inputs & give informative warning messages
- calculate kde
  - store in RAM
  - store in tempfile

## Plot KDE
- ability to adjust angle parameters without recalculating the whole KDE
  - theta & phi
- save to file
  - pdf
  - png
