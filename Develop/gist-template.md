# URL Regex Tutorial C17

Introductory paragraph (replace this with your text)

## Summary
The regex that is explained in this project is to match a URL found on the internet. The regex is written `/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/` and can find most to all URLs with this regex. 

## Table of Contents
- [Regex Components](#regex-components)
- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Character Classes](#character-classes)
- [Character Escapes](#character-escapes)

## Regex Components
`/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`

## Anchors
`/^`(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?`$/`

`/` = start and end of regex

`^` = beginning of the string/line

`$` = end of the string/line

## Quantifiers
/^(https`?`:\/\/)`?`([\da-z\.-]`+`)\.([a-z\.]`{2,6}`)([\/\w \.-]`*`)`*`\/`?`$/

`?` = 0 or 1 values (means optional)

`+` = 1 or more values

`{2,6}` = min and/or max values

`*` = 0 or more values

## Grouping Constructs
/^`(`https?:\/\/`)`?`(`[\da-z\.-]+`)`\.`(`[a-z\.]{2,6}`)(`[\/\w \.-]*`)`*\/?$/

`( )` = captures group values

## Character Classes
/^(https?:\/\/)?(`[\da-z\.-]`+)\.(`[a-z\.]`{2,6})(`[\/\w \.-]`*)*\/?$/

`[ ]` = character class

`\d` = 0-9 (digits)

`a-z` = a-z (lowercase alphabets from a-z)

`\.` = literal period .

### Character Escapes
/^(https?:`\/\/`)?([\da-z`\.-`]+)\.([a-z`\.`]{2,6})([`\/`\w `\.-`]*)*`\/`?$/

`\` = escape code, literal meaning of the following character

`\.-` = literal period . and literal dash -

`\/` = literal slash /

## Author
Esther Choi
https://github.com/yerimechoi
