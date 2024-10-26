<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Two-bit comparator with "ttin:IN0"+"ttin:IN1" being compared to "ttin:IN2"+"ttin:IN3" (Ex. "00" compared to "10" should cause ttout:OUT0 to be high
and the corresponding LED to be turned on).

## How to test

Test combinations of the four inputs following the truth table where ttout:OUT0 will be high if the first two bits are less than the last two bits,
ttout:OUT1 will be high if the first two bits are equal to the last two bits, and ttout:OUT2 will be high if the first two bits are greater than the
last two bits.

## External hardware

3 LED Display with each LED connected to one output.
