# Java Edition

A Minecraft datapack and resource pack that adds a craftable **Coffee Bucket** to the game.

The Coffee Bucket restores hunger, grants temporary Speed and Haste, and has a small chance of causing Nausea, because caffeine always comes with a trade-off.

Check out how it works (the GIF may take a moment to load...):

<p align="center"> <img src="Java-Edition.gif" alt="GIF loading..." width="800"></p>

## Features

- Craftable Coffee Bucket
- Speed I and Haste I for 2 minutes
- Restores 4 nutrition
- 20% chance to apply Nausea for 20 seconds
- Vanilla datapack and resource pack only

## Crafting Recipe

Craft the Coffee Bucket by placing **three Cocoa Beans** in a horizontal row directly above a **Milk Bucket**.

The Milk Bucket may be placed in either the center of the middle row or the center of the bottom row.

## Requirements

- Minecraft Java Edition 1.21.2 or later
- Resource Pack enabled
- Datapack installed in the target world

## Installation

### Resource Pack

Copy the `coffee_rp` folder into:

```
.minecraft/resourcepacks
```

Enable the resource pack from **Options → Resource Packs**.

### Datapack

Copy the `coffee_dp` folder into:

```
.minecraft/saves/<Your World>/datapacks
```

Open the world and run:

```
/reload
```

The Coffee Bucket recipe will now be available.

## Project Structure

```
coffee_dp/
    Datapack containing the crafting recipe and item behavior.

coffee_rp/
    Resource pack containing the Coffee Bucket texture and model overrides.
```
