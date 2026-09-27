# grils-frontline

Public runtime avatar asset host for Oberkommando reporting.

This repository contains only presentation assets used for runtime avatar delivery. It is intentionally separate from private Oberkommando doctrine, profiles, command data, credentials, and Relay state.

## Runtime use

This repository is the established Oberkommando portrait source. Runtime portrait bindings should use stable raw-GitHub URLs from the default branch:

`https://raw.githubusercontent.com/tarodew/grils-frontline/main/avatars/<filename>`

Portrait maintenance belongs here. Do not create a separate portrait-delivery service, restore fragile external hotlinks as the production source, or require Cloudflare Worker modification/deployment merely to change a portrait.

Where an existing reporting/presentation layer cannot consume a valid GitHub-hosted portrait without its own configuration change, treat that as a separate presentation-binding limitation rather than moving portrait ownership out of this repository.

Source/provenance records remain in the private Operational Identity & Portrait Register. Character/game artwork remains the property of its respective rights holders; this repository is not an authority source for canon, identity, or command permissions.
