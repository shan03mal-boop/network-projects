# Network Projects — Cisco Packet Tracer

Enterprise-grade network design and security topologies built in Cisco Packet Tracer.

---

## Project 1 — SwiftCart Enterprise Data Centre & DMZ Network

**File:** `SwiftCart_Network.pkt`

Designed a fully segmented enterprise data centre network for a simulated e-commerce organisation, implementing a three-zone security model separating the internal LAN, DMZ, and external perimeter.

**What was built:**
- DMZ architecture hosting Web, DNS, and FTP servers
- VLAN segmentation with 802.1Q trunking across the switching layer
- NAT/PAT at the perimeter — internal RFC1918 space fully masked
- Inter-VLAN routing with controlled zone-boundary policy
- Spanning Tree Protocol (STP) to eliminate switching loops

**Technologies:** Cisco IOS · VLANs · 802.1Q Trunking · NAT/PAT · DMZ · STP · Inter-VLAN Routing

![SwiftCart Topology](swiftcart-topology.png)

---

## Project 2 — Enterprise Network Security Topology

**File:** `Shehan-E242491_NS_.pkt`

Implemented a hardened enterprise network security topology applying a defence-in-depth strategy across switching and routing layers.

**What was built:**
- Extended and Standard ACLs at inter-VLAN routing boundaries
- Port security with sticky MAC binding and shutdown violation mode
- SSH v2 enforced — Telnet disabled globally across all devices
- VLAN-based security zone segmentation
- Console line hardening with password encryption and exec-timeout
- NAT with ACL-bound permit statements

**Technologies:** Cisco IOS · Extended & Standard ACLs · Port Security · SSH v2 · VLAN Segmentation · NAT · Console Hardening

![Network Security Topology](network-security-topology.png)

---

*Built and validated end-to-end in Cisco Packet Tracer*
