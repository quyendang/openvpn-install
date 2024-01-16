## Installation

First, download the script on your Linux server\*:

```bash
wget -O openvpn.sh https://raw.githubusercontent.com/quyendang/openvpn-install/master/openvpn-install.sh
```

**Option 1:** Auto install OpenVPN using default options.

```bash
sudo bash openvpn.sh --auto
```

<details>
<summary>
See the script in action (terminal recording).
</summary>

**Note:** This recording is for demo purposes only.

<p align="center"><img src="docs/images/demo1.svg"></p>
</details>

For servers with an external firewall (e.g. [EC2](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security-groups.html)/[GCE](https://cloud.google.com/firewall/docs/firewalls)), open UDP port 1194 for the VPN.
