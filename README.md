Modbus - A Home Assistant custom component.
=== 

Install
===

**With HACS**:

- Open HACS
- Select the 3 dots in the top left corver:
  <img width="1061" height="111" alt="select" src="https://github.com/user-attachments/assets/bae0fde3-f6e7-4d3d-b53c-397d1c46d7b3" />

- Choose "personal repositories" and then add repo
  "https://github.com/pymodbus-dev/homeassistant_modbus":

  <img width="404" height="338" alt="add repo" src="https://github.com/user-attachments/assets/e9332384-b050-41fc-a012-af8fc9f2bd90" />

- Back in the HACS overview, click on the repository:
  <img width="1046" height="86" alt="select repo" src="https://github.com/user-attachments/assets/39a64276-4e57-46c8-a452-2afac64caaf3" />

- Download the repository:


  <img width="259" height="143" alt="Download" src="https://github.com/user-attachments/assets/835c1aef-c495-4d6d-80ba-36093f12d8da" />

- Continue in HACS, which will ask you to restart your home assistant instance.

**Manually**:

   copy [modbus](https://github.com/pymodbus-dev/homeassistant_modbus/blob/dev/custom_components/modbus)
   folder into your [custom_components folder](https://developers.home-assistant.io/docs/creating_integration_file_structure/#where-home-assistant-looks-for-integrations).

Enjoy a working modbus, if you encounter a problem feel free to open a issue [direcly](https://github.com/pymodbus-dev/homeassistant_modbus/issues>),
I do also monitor the home assistant issues.


Custom modbus in a nutshell
===

This is a custom component version of the official Homeassistant modbus, The
custom component is Homeassistant modbus++, because the official version is the
base for all commits in here. Whenever the official version changes, this repository
is updated.

REMARK: custom modbus is part of the pymodbus development organisation, connecting it
firmly to pymodbus.


Why a custom component ?
===

The reason involves a bit of history.

I maintained the homeassistant modbus component for years and had 
developer status in the homeassistant repo due to being very active.

For a lot of reasons I decided to take a leave of absence, however my developer
status was untouched.

When I started contributing again, the Core team cancelled my developer status,
signalling that my contributions were no longer welcome.

After talks with several users, I turned my private version into a HACS
custom component, giving modbus users an alternative to the broken official
component.

This is NOT the preferred way, nor the best way, but I saw no other way !


Contributing
===

We actively monitor both homeassistant issues and the homeassistant user forum for
modbus issues, and try to solve them (if possible) the problems in this component.

If we have missed your problem/issue, then please feel free to open an issue in
[here](https://github.com/pymodbus-dev/homeassistant_modbus/issues>)


License Information
===

Released under a modified [APACHE 2 License](https://github.com/pymodbus-dev/homeassistant_modbus/blob/dev/LICENSE)

