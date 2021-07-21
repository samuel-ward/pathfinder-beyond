# Pathfinder `Beyond`: Research

## Overview

This file outlines the research that has been conducted on various areas, and provides a summation of the research insights from https://docs.google.com/document/d/1lcL2mMcCNJjqojB2xV8jPqVSbMv9CsHdz8MQH6F1JR0/edit?usp=sharing

## Sources

### Pathfinder 1e - Core Material

### D&D Beyond

## Conclusions

### Models

```fsharp
type Items =
	| ArmourItem of Armour
	| GearItem of Gear
	| WeaponItem of Weapon

and Armour =
	{

	}

and Gear =
	{

	}

and Weapon =
	{

	}
```

```fsharp
type Class =
	{

	}
```

```fsharp
type Race =
	{

	}
```

```fsharp
type Character =
	{
		Name: string
		Alignment: Alignment
		Race: Race
	}

and Alignment =
	| LawfulGood
	| NeutralGood
	| ChaoticGood
	| LawfulNeutral
	| Neutral
	| ChaoticNeutral
	| LawfulEvil
	| NeutralEvil
	| ChaoticEvil
```