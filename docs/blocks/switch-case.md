---
title: Switch Case
sidebar_position: 1
---

# Switch Case
:::warning
These docs are not completely finished yet. We're slowly working on expanding the documentation while we work on other things, so please be patient with us!
:::

The Switch Case blocks consist of the following blockset:
<img src="/img/docimages/switchcase.png" alt="Switch case Blockset"></img>

## What are they for?
Switch Case blocks can be used to replace large stacks of `if <> then, else` blocks.
They are **not** able to check conditions with booleans, but can check against known values.

<img src="/img/docimages/switchcase_example_ifstack.png" alt="Stack of if else conditions"></img>

The `if <> then, else` chain uses 13 blocks while the Switch Case blocks only use 10.
Each additional `else if <>` branch will use 2 blocks, while `case` blocks only use 1.

They are **not** full replacements for `if` blocks, and can only check against a set of known values.

## Why is this better?
Switch Case blocks are much faster for checking several values, and allow you to use less blocks.

It may also be easier to read your block code later due to the use of less blocks, and
you can re-use code easier with Switch Cases.

## How to setup a Switch Case statement


## Blockset
### switch ()
<img src="/img/docimages/switchcase_switch.png" alt="Switch block"></img>
This block is the start of all other Switch Case blocks.
The spiked notch inside the block should indicate that only case blocks and similar blocks can be placed inside.

