ENGIE La Haute Borne wind farm - public SCADA data (secondary dataset)

Source: ENGIE open data, originally released at opendata-renewables.engie.com
(now offline) under the Etalab Open Licence 2.0. This copy was obtained from
the NREL OpenOA repository: https://github.com/NREL/OpenOA (examples/data/la_haute_borne.zip)

Files
- la-haute-borne-data-2014-2015.csv : 10-minute SCADA averages, 4 turbines
  (R80711, R80721, R80736, R80790), 1 Jan 2014 - 31 Dec 2015, 420,480 rows.
  Columns: Ba_avg (pitch), P_avg (active power), Ws_avg (wind speed),
  Va_avg (vane position), Ot_avg (outdoor temp), Ya_avg (nacelle angle),
  Wa_avg (wind direction)
- la-haute-borne_asset_table.csv : turbine locations and specifications
- SCADA_data_description.csv : variable definitions
- plant_data.csv : plant-level meter/availability/curtailment data
  (NOTE: synthesized by the OpenOA developers, not original ENGIE data)
- era5_wind_la_haute_borne.csv, merra2_la_haute_borne.csv : reanalysis wind data

Fuller 2013-2018 coverage: Mendeley Data, DOI 10.17632/vmyg4yp3s8.1

This is the raw public data only. It contains no fault labels, maintenance logs,
vibration, gearbox temperature or torque columns.
