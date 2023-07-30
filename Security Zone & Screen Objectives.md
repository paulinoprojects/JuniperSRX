# Security Object 
## Security Object: Zone
### What is a Security Zone
- A security zone is a logical entity that groups one or more interfaces that require the regulation of inbound and outbound traffic through policies.
- Security zones are used to divide the network into different segments, and to apply different security policies to each segment.

### Why use Security Zones?
- Increased security: Security zones can help to protect your network from unauthorized access. By dividing your network into different segments, you can apply different security policies to each segment, which can help to prevent attackers from exploiting vulnerabilities in one segment to gain access to other segments.
- Improved traffic management: Security zones can help you to control traffic flow within your network. For example, you might create a security zone for your DMZ, and then create security policies that allow only certain types of traffic to flow between the DMZ and your internal network. This would help to protect your internal network from attacks that originate from the DMZ.
- Easier administration: Security zones can make it easier to manage your network security policies. By grouping interfaces into security zones, you can simplify the process of creating and managing security policies.

### How are security zones configured?
- Security zones are configured on Juniper SRX devices using the <security-zone> command. The <security-zone> command takes a zone name as an argument, and then specifies the interfaces that should be assigned to that zone.

### What are the different types of security zones?

There are two main types of security zones: Layer 2 security zones and Layer 3 security zones. 
- Layer 2 security zones are used to control traffic on Layer 2 interfaces.
- Layer 3 security zones are used to control traffic on Layer 3 interfaces.