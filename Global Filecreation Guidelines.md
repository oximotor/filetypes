Every raw file will start with the hex digits

`4F 58 49` "OXI"

followed by a single byte denoting the custom file type.

These filetypes MUST be logged in the table below in order to prevent overlap.

| Hex Byte | Filetype |
|:--------:|:--------:|
| 00 | Reserved |



The goals of the engine is to run efficiently and to be space optimized, final engine filetypes should reflect this (Intermediary pre-compile filetypes do not have to reflect this, but please, be reasonable. Also intermediary files have less of a need to be custom, so prioritize FEFs).