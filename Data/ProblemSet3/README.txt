AWS Data Variables and Notes:

Date - date and time (in UTC) that the data points in that row were measured
T_surf - temperature of the ice surface in degrees Celsius
T_sub - temperature of the subsurface at 1 meter depth in degrees Celsius
T_air - temperature of the air at 2 meters above the surface in degrees Celsius
SW_d - downwelling shortwave radiation in Watts per meter squared
SW_u - upwelling shortwave radiation in Watts per meter squared
LW_d - downwelling longwave radiation in Watts per meter squared
LW_u - upwelling longwave radiation in Watts per meter squared
SHF - sensible heat flux in Watts per meter squared, calculated from the gradient of wind speed and temperature between the surface and the station's 
upper boom, aerodynamic roughness was set to 0.001 m.
LHF - latent heat flux Watts per meter squared, calculated from the gradient of wind speed and humidity between the surface and the station's upper 
boom, aerodynamic roughness was set to 0.001 m.
dH - depth of a pressure transducer below the surface of the ice in meters. If values get less negative over time, this indicates a thinning of the 
overlying ice and gives a measure of the total ice ablated over that time period.