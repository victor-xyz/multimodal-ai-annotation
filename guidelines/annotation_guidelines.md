# Multimodal Annotation Guidelines

## Core Rule

Annotate what can reasonably be established from visual evidence. Do not invent identity, intent, private attributes, relationships, or other information that the media does not support.

## People

Record observable information such as number of people, visible activity, clothing or accessories when relevant, body position, movement, and interaction with visible objects.

Avoid guessing identity, exact age, personal background, or private attributes.

## Objects

Identify salient objects that contribute to the scene. Use specific labels when confident; otherwise use an appropriate broader category.

## Actions

Describe observable actions using neutral language.

Prefer: "person is holding a cup" or "person walks towards the vehicle."

Avoid unsupported interpretations such as "person is celebrating" or "person is angry" unless the evidence clearly supports the interpretation and the schema permits it.

## Relationships and Interactions

Record observable relationships between entities, such as person holding object, person standing beside vehicle, two people facing each other, or vehicle approaching pedestrian.

## Environment

Capture relevant setting information such as indoor/outdoor, road, office, classroom, shop, park, and clearly observable environmental conditions.

## Video and Temporal Context

Preserve event order and use timestamps or frame ranges where available.

## Uncertainty

When an observation is unclear, record uncertainty rather than inventing detail.

Useful labels:
- `clear`
- `likely`
- `uncertain`
- `not_visible`

## Quality Control Checklist

- Is every label supported by visual evidence?
- Are objects and actions described consistently?
- Have unsupported assumptions been removed?
- Is temporal order correct?
- Are ambiguous observations marked?
- Is the JSON valid?
