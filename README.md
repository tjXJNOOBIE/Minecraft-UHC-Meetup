# Minecraft-UHC-Meetup

Single-instance Minecraft UHC Meetup plugin from the 2016/2017 era. The project focuses on fast UHC-style combat rounds, player spawning, combat rules, statistics, and match lifecycle management.

## What It Does

- Runs a UHC Meetup match on one Minecraft server instance.
- Provides commands for starting games, checking stats, spectating, health display, and world creation.
- Handles block rules, creature spawning, damage control, deaths, lobby events, spectator behavior, scoreboards, rain control, and void protection.
- Includes MySQL-backed game ID and stat helpers for persistent match records.

## Repository Layout

- `src/commands/` - player and host command handlers.
- `src/events/` - UHC Meetup game, lobby, combat, spectator, and environment listeners.
- `src/mysql/` - persistence helpers for game IDs and stats.

## Tech Stack

- Java
- Bukkit/Spigot-style plugin APIs
- MySQL-backed stat tracking

## Status

Archived historical game-mode plugin. It is retained as a reference for older UHC Meetup gameplay systems and network-era plugin development.
