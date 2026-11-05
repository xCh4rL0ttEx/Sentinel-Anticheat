# Sentinel-Anticheat

Sentinel-Anticheat is an anti-cheat system for Minecraft Bedrock that detects hacked clients and cheating behavior, built to work alongside [Sentinel-Database](https://sentinel-database.org).

Cheating ruins the experience for everyone else on a server. Sentinel-Anticheat gives Bedrock server owners a way to catch it, act on it, and share what they learn with the wider community.

---

## Overview

Sentinel-Anticheat watches for the signs of hacked clients and unfair play on your Bedrock server. When something looks wrong, it flags the player so you can review and respond. It is designed to connect with Sentinel-Database, a community project that logs, verifies and archives player behavior across servers, tracks repeat offenders, and shares intelligence with security networks.

Together, the two projects aim to make it harder for known cheaters to move from server to server unnoticed.

## Features

- **Hacked client detection:** identifies behavior and signatures associated with known Bedrock hack clients
- **Cheating behavior checks:** flags suspicious movement, combat and gameplay patterns
- **Sentinel-Database integration:** report detections and check players against community records
- **Configurable responses:** decide what happens when a player is flagged (log, alert staff, kick, ban)
- **Built for Bedrock:** made specifically for Minecraft Bedrock Edition servers

> Edit this list to match what is actually implemented. Remove anything that is still planned.

## How It Works

1. A player joins or plays on your server.
2. Sentinel-Anticheat monitors their behavior and client information.
3. If a check is triggered, the player is flagged and the event is logged.
4. Your configured action runs, such as alerting staff or removing the player.
5. With Sentinel-Database connected, the detection can be reported and cross-referenced against the community archive.

## Getting Started

### Requirements

- A Minecraft Bedrock Edition server
- [Add your platform, runtime or software requirements here]

### Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/Sentinel-Anticheat.git
cd Sentinel-Anticheat

# Add your install or build steps here
```

### Configuration

Copy the example config and adjust it to suit your server:

```bash
cp config.example.yml config.yml
```

Key options to review:

| Option | Description |
| --- | --- |
| Detection checks | Which checks are enabled and how strict they are |
| Punishments | What happens when a player is flagged |
| Sentinel-Database | Connection settings for reporting and lookups |
| Logging | Where and how detections are recorded |

> Update the file name and options above to match your real configuration.

## Sentinel-Database Integration

[Sentinel-Database](https://sentinel-database.org) is a community project that tracks Minecraft Bedrock hackers and hack clients. When connected, Sentinel-Anticheat can:

- Report confirmed detections to the database
- Check joining players against known repeat offenders
- Help build a shared record that benefits other servers

Integration is optional, and the anticheat can run on its own.

## Contributing

Contributions are welcome. If you want to help:

1. Fork the repository
2. Create a branch for your change
3. Commit your work with a clear message
4. Open a pull request describing what you changed and why

Bug reports, detection ideas and false positive reports are especially useful. Please open an issue with as much detail as you can.

## Reporting False Positives

No anti-cheat is perfect. If a legitimate player is flagged, open an issue with the check that triggered, what the player was doing, and any logs you have. This helps keep detections accurate and fair.

## Community

Join the community on [Discord](https://discord.com/invite/ETujuybCGW) for support, discussion and updates.

## License

[Add your chosen license here, for example MIT]

## Disclaimer

Sentinel-Anticheat is not affiliated with or endorsed by Mojang Studios or Microsoft. Minecraft is a trademark of Mojang Studios.
