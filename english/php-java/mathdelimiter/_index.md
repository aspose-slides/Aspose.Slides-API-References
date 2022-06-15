---
title: MathDelimiter
type: docs
weight: 0
url: /php-java/mathdelimiter/
---

# MathDelimiter class

 Specifies the delimiter object, consisting of opening and closing characters (such as parentheses, 
 braces, brackets, and vertical bars), and one or more mathematical elements inside, separated by a specified character.
 Examples: (?2); [?2|?2]
 
Example:
 
```php
  $element = new MathematicalText("x");
  $delimiter = new MathDelimiter($element);
```

## Constructors

| name | description |
| --- | --- |
| [MathDelimiter](/php-java/mathdelimiter/mathdelimiter/)(IMathElement) | Initializes MathDelimiter with the specified element as single base argument |

## Methods

| name | return type | description |
| --- | --- | --- |
| [delimit](/php-java/mathdelimiter/delimit/)(char) | IMathDelimiter | Delimits arguments using the specified delimiter character |
| [enclose](/php-java/mathdelimiter/enclose/)(char, char) | IMathDelimiter | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [getArguments](/php-java/mathdelimiter/getarguments/)() | IMathElementCollection | One or more mathematical elements separated by delimiter characters |
| [getBeginningCharacter](/php-java/mathdelimiter/getbeginningcharacter/)() | char | Delimiter Beginning Character specifies the beginning, or opening, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: '('. |
| [getChildren](/php-java/mathdelimiter/getchildren/)() | IMathElement | Get children elements |
| [getDelimiterShape](/php-java/mathdelimiter/getdelimitershape/)() | int | Specifies the shape of delimiters in the delimiter object. When is MathDelimiterShape.Centered, delimiters are centered around the math axis of the mathematical text and still be made to fit the entire height of their contents. When is MathDelimiterShape.Match, their height and shape are altered to exactly match their contents. |
| [getEndingCharacter](/php-java/mathdelimiter/getendingcharacter/)() | char | Delimiter Ending Character specifies the ending, or closing, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: ')'. |
| [getGrowToMatchOperandHeight](/php-java/mathdelimiter/getgrowtomatchoperandheight/)() | boolean | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. The default value is true |
| [getSeparatorCharacter](/php-java/mathdelimiter/getseparatorcharacter/)() | char | Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'. |
| [setBeginningCharacter](/php-java/mathdelimiter/setbeginningcharacter/)(char) | void | Delimiter Beginning Character specifies the beginning, or opening, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: '('. |
| [setDelimiterShape](/php-java/mathdelimiter/setdelimitershape/)(int) | void | Specifies the shape of delimiters in the delimiter object. When is MathDelimiterShape.Centered, delimiters are centered around the math axis of the mathematical text and still be made to fit the entire height of their contents. When is MathDelimiterShape.Match, their height and shape are altered to exactly match their contents. |
| [setEndingCharacter](/php-java/mathdelimiter/setendingcharacter/)(char) | void | Delimiter Ending Character specifies the ending, or closing, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: ')'. |
| [setGrowToMatchOperandHeight](/php-java/mathdelimiter/setgrowtomatchoperandheight/)(boolean) | void | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. The default value is true |
| [setSeparatorCharacter](/php-java/mathdelimiter/setseparatorcharacter/)(char) | void | Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'. |
