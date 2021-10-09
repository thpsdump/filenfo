# relnfo

## project
this is an effort to catalog all thps releases at a file level with a priorty on beta/prototypes. the data will aid in analysis of the relationships and timelines for releases. the same method may be used to feed svgt @ timeline.mameau.com for other titles in the future

this repo is the main info dump with the intent for this data to collated into a usable form e.g. sql with web frontend or similar.

still need to identify tools for more systems so we can process the dumps

## structure
directory structure (per entry)

```
./hash
./hash/hash-struct.txt *
./hash/hash-extract.log *
./hash/hash-data.md5
./hash/hash-image.md5
./hash/hash.cat *
./hash/hash.cue
./hash/hash.names
./hash/hash.notes *
./hash/data
```
\* are optional or may differ between tools


## tools
a list of tools feeding this project
| system | tool | link |
| - |-|-|
| psx | psximager    | https://github.com/cebix/psximager         |
| psx | thps2-tools  | https://github.com/JayFoxRox/thps2-tools   |
| psx | toc2cue      | -                                          |
| psx | bchunk       | -                                          |
| xbox| extract-xiso | https://github.com/XboxDev/extract-xiso |


reference for tools to review for other systems
| system | tool | link |
| - |-|-|
| dc  | gditools     | https://sourceforge.net/projects/dcisotools |
| gc  | gciso        | https://github.com/pfirsich/gciso |
| wii | wit          | https://wit.wiimm.de/wit/ |
| psx | dumpid.py    | https://gist.github.com/i30817/96674a3de8d9e4cb890e92cec3f36990 |
