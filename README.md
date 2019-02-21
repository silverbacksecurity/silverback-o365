# silverback-o365 - This is a Palo Alto Networks xml template to load some O365 best practices, it is missing EDLs. 
 
load config partial from O365-Uber-Rules.xml from-xpath /config/devices/entry[@name='localhost.localdomain']/rulebase/security to-xpath /config/devices/entry[@name='localhost.localdomain']/vsys/entry[@name='vsys1']/rulebase/security mode merge
