# Regular Expressions (regex) Tutorial

This trutorial will give you a basic understanding of the key concepts of Regular Expressions, also known as Regex.

## Summary

In JavaScript, a Regular Expression (RegEx) is an object that describes a sequence of characters used for defining a search pattern. I'll be giving you an overview of everything you need to know about Regula Expressions.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components


### Anchors

Unlike other regular expression tokens, Anchors don't match actual characters. Anchors match a position before, after, or between characters. You'll see what I mean once you see an example.

### Quantifiers
Quantifiers specify how many instances of a character, group, or character class must be present in the input for a match to be found. The following table lists the quantifiers supported by .NET:

### OR Operator
You can use the | operator (logical OR) to match characters or expression of either the left or right of the | operator. 
### Character Classes
Character Classes are items that appear between two squar brackets [ ]. It specifies the characters that will successfully match a single character from a given input string.

### Flags
A regular expression consists of a pattern and optional flags: g , i , m , u , s , y . Without flags and special symbols (that we'll study later), the search by a regexp is the same as a substring search. The method str. match(regexp) looks for matches: all of them if there's g flag, otherwise, only the first one.

### Grouping and Capturing
Capturing groups are a way to treat multiple characters as a single unit. They are created by placing the characters to be grouped inside a set of parentheses. For example, the regular expression (dog) creates a single group containing the letters "d" "o" and "g" .

### Bracket Expressions
A bracket expression (an expression enclosed in square brackets, "[]" ) is an RE that shall match a specific set of single characters, and may match a specific set of multi-character collating elements, based on the non-empty set of list expressions contained in the bracket expression.

### Greedy and Lazy Match

Greedy Match — will try to match the longest possible string.

Lazy Search — will try to match the smallest possible string. Append ? to make the search lazy.



### Boundaries
The (\b) is an anchor like the caret (^) and the dollar sign ($). It matches a position that is called a “word boundary”. The word boundary match is zero-length.

### Back-references
Backreferences match the same text as previously matched by a capturing group. Suppose you want to match a pair of opening and closing HTML tags, and the text in between. By putting the opening tag into a backreference, we can reuse the name of the tag for the closing tag. 


### Look-ahead and Look-behind
Lookahead and lookbehind, collectively called “lookaround”, are zero-length assertions just like the start and end of line, and start and end of word anchors explained earlier in this tutorial. The difference is that lookaround actually matches characters, but then gives up the match, returning only the result: match or no match. That is why they are called “assertions”. They do not consume characters in the string, but only assert whether a match is possible or not.

## Author
Ndubuisi Azi is a finance professional at a regional bank, who has recently taking up coding. He is on his way to completing a coding bootcamp. to find out more about the projects Ndubuisi has worked visit his gitup here https://github.com/ndubuisiazi

