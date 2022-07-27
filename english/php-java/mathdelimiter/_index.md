---
title: MathDelimiter
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/mathdelimiter/
---

## MathDelimiter class

 Specifies the delimiter object, consisting of opening and closing characters (such as parentheses, 
 braces, brackets, and vertical bars), and one or more mathematical elements inside, separated by a specified character.
 Examples: (?2); [?2|?2]
 
Example:
 
```php
  $element = new MathematicalText("x");
  $delimiter = new MathDelimiter($element);
```

## Constructors

| Name | Description |
| --- | --- |
| [MathDelimiter](mathdelimiter)([MathLeftSubSuperscriptElement](../mathleftsubsuperscriptelement)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathLimit](../mathlimit)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathMatrix](../mathmatrix)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathBlock](../mathblock)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathRadical](../mathradical)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathArray](../matharray)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathDelimiter](../mathdelimiter)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathNaryOperator](../mathnaryoperator)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathAccent](../mathaccent)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathBorderBox](../mathborderbox)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathGroupingCharacter](../mathgroupingcharacter)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathBar](../mathbar)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathSuperscriptElement](../mathsuperscriptelement)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathFunction](../mathfunction)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathSubscriptElement](../mathsubscriptelement)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathFraction](../mathfraction)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathematicalText](../mathematicaltext)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathBox](../mathbox)) | Initializes MathDelimiter with the specified element as single base argument |
| [MathDelimiter](mathdelimiter)([MathRightSubSuperscriptElement](../mathrightsubsuperscriptelement)) | Initializes MathDelimiter with the specified element as single base argument |

## Methods

| Name | Description |
| --- | --- |
| [delimit](delimit)(char) | Delimits arguments using the specified delimiter character |
| [enclose](enclose)(char, char) | Encloses a math element in specified characters such as parenthesis or another characters as framing |
| [getArguments](getarguments)() | One or more mathematical elements separated by delimiter characters |
| [getBeginningCharacter](getbeginningcharacter)() | Delimiter Beginning Character specifies the beginning, or opening, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: '('. |
| [getChildren](getchildren)() | Get children elements |
| [getDelimiterShape](getdelimitershape)() | Specifies the shape of delimiters in the delimiter object. When is MathDelimiterShape.Centered, delimiters are centered around the math axis of the mathematical text and still be made to fit the entire height of their contents. When is MathDelimiterShape.Match, their height and shape are altered to exactly match their contents. |
| [getEndingCharacter](getendingcharacter)() | Delimiter Ending Character specifies the ending, or closing, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: ')'. |
| [getGrowToMatchOperandHeight](getgrowtomatchoperandheight)() | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. The default value is true |
| [getSeparatorCharacter](getseparatorcharacter)() | Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'. |
| [setBeginningCharacter](setbeginningcharacter)(char) | Delimiter Beginning Character specifies the beginning, or opening, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: '('. |
| [setDelimiterShape](setdelimitershape)(int) | Specifies the shape of delimiters in the delimiter object. When is MathDelimiterShape.Centered, delimiters are centered around the math axis of the mathematical text and still be made to fit the entire height of their contents. When is MathDelimiterShape.Match, their height and shape are altered to exactly match their contents. |
| [setEndingCharacter](setendingcharacter)(char) | Delimiter Ending Character specifies the ending, or closing, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: ')'. |
| [setGrowToMatchOperandHeight](setgrowtomatchoperandheight)(boolean) | Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. The default value is true |
| [setSeparatorCharacter](setseparatorcharacter)(char) | Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'. |
