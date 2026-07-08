# 🔒 Why Neon Tunnel is Closed Source?

For those who come with questions like "where's the source code?", "why can't I fork it?", "what if there's a virus?" — read carefully.

Neon Tunnel is completely free. I don't charge a single penny. But the code is closed — and there are reasons for that.

## What You Get for Free

- Full-featured VPN client for Windows without subscriptions or limitations
- DPI bypass, Game Tunnel mode, support for 6+ protocols
- Beautiful GUI with 3D and color themes
- No ads, no premium tier, no telemetry
- Regular updates and support

That's it. Free. As in "completely free".

## Why the Code is Closed

### 1. Because Free Work Gets No Respect

I'm building this project for my portfolio — as proof of my skills. It doesn't generate any income for me. Not a single penny. I spend my free time on it.

When code is open, predictable things happen:

- People fork it, slap their logo on it, and distribute it as "their own"
- Demands start pouring in: "fix this, add that, why isn't feature X here?" — for free, of course
- Vulnerabilities are found and used against users instead of being reported to me
- Roskomnadzor (Russian internet regulator) comes and blocks the repository along with all forks

Closed source isn't paranoia. It's protecting the project from itself.

### 2. Because "Open Source ≠ Security"

Common myth: "if the code is open, it must be secure." No. OpenSSL was open — and Heartbleed existed for years. Log4j was open — and the entire internet infrastructure burned.

Open code doesn't make software secure. A responsible developer makes software secure.

### 3. Because Bypassing Blocks is a Sensitive Area

The application uses specific methods to bypass network restrictions. If the code were open, these methods would be available for analysis and patching — and would stop working.

Closed source protects users: as long as the implementation isn't publicly available, the methods remain effective longer.

## "What If There's a Virus?" — Let's Look at the Facts

### VirusTotal: Check Passed

The NeonTunnel.exe application has been checked on [VirusTotal](https://www.virustotal.com) — a service that scans files with 70+ antivirus engines simultaneously.

Result: 1.68 detections out of ~72 engines.

The only antivirus that flags it is Kaspersky, and only on the WinDivert component — a legitimate network packet capture driver with open source code ([github.com/basil00/WinDivert](https://github.com/basil00/WinDivert)), which is used by thousands of projects worldwide.

No trojans. No spyware. No miners. No stealers. Nothing.

### What the Application Does with the Network

Neon Tunnel connects only to:

| Where | Why |
| --- | --- |
| github.com/northlightcode/neon-tunnel | Update checks (and that's it) |
| Your VPN server | Traffic proxying (you specify it yourself) |

That's it. No analytics servers. No telemetry. No "call home". No hidden endpoints.

You can verify this yourself — sniff the traffic, check Process Monitor, monitor network connections. The application doesn't reach out anywhere except GitHub and your server.

### What the Application Does NOT Do

❌ Does not collect personal data  
❌ Does not send usage statistics  
❌ Does not show ads  
❌ Does not install background services  
❌ Does not modify system files (except network settings while running)  
 Does not require internet to work (except for update checks at launch)

## What's Actually in the Closed Code

Neon Tunnel is a GUI wrapper around proven open-source components:

| Component | Source Code | Role |
| --- | --- | --- |
| Xray | [github.com/XTLS/Xray-core](https://github.com/XTLS/Xray-core) | Tunnel core (VLESS, VMess, Trojan, Shadowsocks) |
| sing-box | [github.com/SagerNet/sing-box](https://github.com/SagerNet/sing-box) | Tunnel for Game mode (Hysteria2, TUIC) |
| WinDivert | [github.com/basil00/WinDivert](https://github.com/basil00/WinDivert) | Network packet capture |
| zapret | [github.com/bol-van/zapret](https://github.com/bol-van/zapret) | DPI bypass ("DPI Only" mode) |

My closed code is the graphical interface, orchestration of these components, and custom bypass methods. Everything else is open code that can be verified.

## What I Guarantee

- The application is free — and will remain so. No subscriptions, no donations, no hidden payments.
- No telemetry — verified by VirusTotal and any sniffer.
- Open dependencies — Xray, sing-box, WinDivert, zapret — all can be verified.
- Updates only through GitHub Releases — no third-party servers.
- MPL-2.0 license — you can use, modify, and distribute, but with conditions.

## If You Still Don't Trust It

That's your right. Don't install it. Use any other VPN.

But know this: I'm building this project not for money, not for fame, and not to deceive you. I'm building it because I enjoy writing code, and because I believe access to information is a fundamental right.

Closed source is my way of protecting the project from people who would come to ruin it.

**Neon Tunnel — free, secure, closed. Three words that can coexist.**

---

📬 Questions and suggestions: [t.me/N30Ntunnel](https://t.me/N30Ntunnel) | northernlightsss@proton.me
