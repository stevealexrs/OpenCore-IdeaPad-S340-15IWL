# OpenCore IdeaPad S340-15IWL
 
### EFI files for OpenCore 0.6.7

Specs


| Features | Status |
|----------|--------|
| Battery  | Not working |
| Touchpad | Not working |
| Keyboard | Mostly |
| WiFi | Working |
| 


## Peculiar Bugs
Removing "-v keepsyms=1" fromm= boot-args in config.plist will cause startup failure. 
 
## Battery
Not working due to missing SMCBatteryManager. It is omitted here because lack of an easy patching guide.
Note: DO NOT use it without patching even though it may boot because it causes bugs like black screen after verbose boot.

## Touchpad
