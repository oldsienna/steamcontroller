# steamcontroller
Steam Controller Template for HELLDIVERS

The Steam Controller is an ideal device for automating Stratagem codes (macro) that can be assigned to a single button. Here's an example of a customisation that's come about through dozens of hours of trial and error. The following has been remapped for a frequently used load-out:

- LEFT BUMPER: Reinforce Stratagem
- RIGHT BUMPER: Reload. HOLD for map
- ESCAPE: REC-6 Demolisher Stratagem
- X BUTTON: Close Air Support Stratagem
- BACK LEFT: Dive prone / Get up / Jump. HOLD for turbo "recover" i.e. mashing A button
- BACK RIGHT: Left Bumper (hold to call other Stratagems)
- MENU: Start button
  
Installation: 
1. Copy VDF file into folder: \Program Files (x86)\Steam\controller_base\templates
1. From Steam client: Right-Click HELLDIVERS > Manage > Controller Configuration
1. Browse Configs > Templates > Lazy HELLDIVER Binding

Edit the VDF file to further customise buttons for additional Stratagem automation. Make use of **HOLD** and **DOUBLE TAP** settings to assign even more.

Tips for Mapping Stratagems:
- Set the delay_end for SHOULDER_LEFT to max of 1000 (hold down for 1 second) then sequence the codes in 100 incrementals
- Set the first d-pad button with a delay_start of 100 then add 100 for subsequent buttons
- Adjust the delay_end to cover the entire sequence e.g. 500 for a 4-code Stratagem, 600 for a 5-code etc
- End the sequence with a TRIGGER_RIGHT to auto-throw the Stratagem
- Optionally remove the SHOULDER_LEFT and TRIGGER_RIGHT from the automation to semi-automate the Stratagem i.e. hold down BACK RIGHT + press assigned button for automated sequence + RIGHT TRIGGER to then throw
- There is potential to decrease the total activation time by reducing the increment values but this may reduce reliability

For those using the keyboard and mouse or other types of controllers, the above can also be achieved with tools like AutoHotKey and reWASD.
