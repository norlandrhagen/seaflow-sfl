# seaflow-sfl

SFL files contains metadata for each SeaFlow files recorded during the cruise. These metadata are provided by the ship's data broadcast system and are being copied to the SeaFlow instrument as is (uncurated).

The metadata contains the following information:
FILE: SeaFlow filename
DATE: data and time in GMT
FILE DURATION: acquisition time (in sec, usually 180s)
LAT: latitude (deg N)
LON: longitude (deg W)
CONDUCTIVITY:
SALINITY: seawater salinity (psu)
OCEAN TEMP: seawater temperature (deg C)
PAR: Photosynthetic Active Radiations above surface water
BULK RED: bulk chlorophyll
STREAM PRESSURE: pressure of the sample (psi), usually set at 12
FLOW RATE: flow rate of the sample (µL min-1) based on stream pressure
EVENT RATE: number of events recorded per second (should be below 18,000 for quality data)
