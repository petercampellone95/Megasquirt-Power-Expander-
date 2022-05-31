# Megasquirt-Power-Expander-

Breakout board for Megasquirt 3 standalone automotive ECU to fanout 5VREF, ECU_GND, +12V, and CHASSIS_GND signals to mulitple headers so it is far easier to connect sensors, oxygen sensors/controllers, gauges, and more. 


Changelog:
V0.2: Removed traces for all power rails, replaced with power planes due to large startup current draw of wideband 02 sensor (~3A). Not entirely necessary but definitely safer, may need to add passive filtering if coupled noise becomes an issue. 

V0.1: Initial design
