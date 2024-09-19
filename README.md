# router-configs
Known good base router configs for Quic Broadband

This includes a range of configurations across vendors for DHCP and PPPoE, with or without WAN VLAN tagging to the ONT.

FIlenames should be in the format
```vendor-protocol-vlan.conf```
E.g. for a MikroTik DHCP config with no VLAN (untagged)
```mikrotik-dhcp-untagged.conf```
Or for a Fortinet with PPPoE and VLAN 10 (tagged)
```fortinet-pppoe-tagged.conf```
