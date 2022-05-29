# homeassistant-ttc-zones
Custom Zones for Home Assistant for the Toronto TTC Subway Stations

Credit to https://twitter.com/scruss for the original GPS locations of the stations. I've added newer stations from maps. Accuracy may be out by a few meters, but this should be enough to get you started.

1. Create a zones.yaml file in your Home Assistant configuration folder.
2. Edit configuration.yaml and add zone: !includes zones.yaml
3. Reload zones from Developer Tools
