# 8086 Physical Address Calculator

A simple web-based tool that calculates the 20-bit physical address of the Intel 8086 microprocessor from a segment and offset value.

## Formula

Physical Address = (Segment × 10h) + Offset

The segment value is shifted left by 4 bits (one hex digit) and then the offset is added.

## How to Use

1. Enter the Segment address in hexadecimal.
2. Enter the Offset address in hexadecimal.
3. Click Calculate to see the physical address.

## Example

| Segment | Offset | Physical Address |
|---------|--------|------------------|
| 2000h   | 0050h  | 20050h           |

Working: 2000h × 10h = 20000h, then 20000h + 0050h = 20050h

## Files

- `index.html`: the calculator (HTML, CSS and JavaScript)

## Author

pranotiPpatil
