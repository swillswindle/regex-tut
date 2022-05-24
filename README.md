# Regular Expressions (regex) 

What are Regular Expressions?


Also known as regex, regexp, or sometimes rational expressions, they are a sequence of characters that describe a "search pattern," in text.
On their own, they don't actually do anything until they're interpreted by a string-searching algorithm that applies the pattern to a string of text, looking to match the search pattern against the sequence of characters present within the targeted string.

It's possible to write regex in various different syntaxes, with two of the most popular being POSIX and Perl.

Regex are composed of "literal characters," and "metacharacters."

Literal characters are exactly that: a literal representation of the character that you want to match.

Metacharacters on the other hand, are a bit more complicated. Essentially they are characters that have been repurposed to represent a more function-like search parameter.

For example, a very basic regex can be as simple as: 

`b.`

Looks fairly simple right? It is. "b" is a literal character, and will match any instance of the character within the targeted string. Bear in mind that this is explicitly literal, and therefore would not match "B", as lowercase and uppercase characters are distinct within computer character sets like ASCII and Unicode, even though in speech and language they are functionally equivalent. 


"." is a metacharacter that will match ANY character, except the start of a new line. So, this regular expression would match "ba", "bb", "b1", "b!"... etc

Regex are capable of 


## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
