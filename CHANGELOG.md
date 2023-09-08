# Change Log

All notable changes to the "system-z" extension will be documented in this file.

## [0.1.0]

- Initial release

## [0.2.0]

- Unique highlighting for action keywords

### [0.2.1]

- Updated extension display name from "system-z" to System Z
- Updated README

### [0.2.2]

- Minor updates to metadata

### [0.2.3]

- Added missing keywords
- Allow whitespace before comments

### [0.2.4]

- Fix incorrect highlighting for tags

## [0.3.0]

- Modified highlighting of hexadecimal values
- Added more missing keywords
- When at the beginning of a line, '--' now denotes an inline comment

### [0.3.1]

- Moved RECLEN, DEC, and OCCURS to "types" instead of "keywords"
- Moved WADSP and WORK to "action keywords"

### [0.3.2]

- Move PASSWORD to "action keywords"
- Added keywords LPP, IOSTATUS
- Move TIMES to "types" instead of "keywords"
- Add temporary icon to project

## [0.4.0]

- Add special highlighting for reserved datanames
- Change highlighting for file declarations
- Removed "special" highlighting category

## [0.5.0]

- Move INPUT, OUTPUT, I-O, EXTEND, and TABR to "action keywords"
- File names are now highlighted in ALL locations (not just at declaration)
- Add special highlighting for CALLs, CHAINs, and CHAINRs

### [0.5.1]

- Add MANY missing reserved datanames and keywords (hopefully for the final time)
- Allow highlighting for COBOL field declarations
- Switched highlighting priorities to make things more accurate
- Found most, if not all, of the programs that are packaged with Z
    - These are now all highlighted and italicized like the "S$" programs

### [0.5.2]

- Fixed some edge cases where TAGs were being highlighted incorrectly
- Fixed an incomplete pattern for the GR (GRAPHICS) keyword

## [0.6.0]

- Change the way CALLs and CHAINs are highlighted (ALL target programs are italicized)
- Numbers now allow the sign at the end of the number

### [0.6.1]

- Changed the coloring of some keywords to be more accurate (UP, HOME, etc.)
    - No new keywords were added, only recategorized