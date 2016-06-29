#### `settings/carb_ratios.json`
This report contains your carb ratios.
##### Setup code
`openaps report add settings/carb-ratios.json JSON pump read_carb_ratios`
##### Sample contents
`{
  "units": "grams", 
  "raw": "0x01 0x00 0x05 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00 0x00", 
  "first": 1, 
  "schedule": [
    {
      "start": "00:00:00", 
      "r": 5, 
      "ratio": 5, 
      "offset": 0, 
      "i": 0, 
      "x": 0
    }
  ]
}`
##### Dependencies
* [`pump.ini`](openaps-device-pump.md)