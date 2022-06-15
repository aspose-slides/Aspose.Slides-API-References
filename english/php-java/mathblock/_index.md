---
title: MathBlock
type: docs
weight: 0
url: /php-java/mathblock/
---

# MathBlock class

 Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line.
 All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.
 
Example:
 
```php
  $mathBlock = new MathBlock();
```

## Constructors

| name | description |
| --- | --- |
| [MathBlock](/php-java/mathblock/mathblock/)() | Initializes a new instance of the MathBlock class. |
| [MathBlock](/php-java/mathblock/mathblock/)(IMathElement) | Creates a new mathematical block and puts specified element in it |
| [MathBlock](/php-java/mathblock/mathblock/)(com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement>) | Creates a new mathematical block and puts specified elements in it |

## Methods

| name | return type | description |
| --- | --- | --- |
| [add](/php-java/mathblock/add/)(IMathElement) | void | Adds a math element to the end of the collection. |
| [clear](/php-java/mathblock/clear/)() | void | Removes all elements from the collection. |
| [contains](/php-java/mathblock/contains/)(IMathElement) | boolean | Determines whether the collection contains a specific value. |
| [copyTo](/php-java/mathblock/copyto/)(com.aspose.slides.IMathElement[], int) | void | Copy to specified array. |
| [delimit](/php-java/mathblock/delimit/)(char) | IMathDelimiter | Delimits child elements with separator character (without the brackets) |
| [enclose](/php-java/mathblock/enclose/)(char, char) | IMathDelimiter | Encloses child elements of this block in specified characters such as parenthesis or another characters as framing |
| [enclose](/php-java/mathblock/enclose/)(char, char, char) | IMathDelimiter | Encloses child elements of this block in specified characters such as parenthesis or another as framing and delimit with a separator character |
| [getChildren](/php-java/mathblock/getchildren/)() | IMathElement | Get children elements |
| [getCount](/php-java/mathblock/getcount/)() | int | Gets the number of child math elements actually contained in the collection. Read-only int. |
| [get_Item](/php-java/mathblock/get_item/)(int) | IMathElement | Gets or sets IMathElement at the specified index. |
| [indexOf](/php-java/mathblock/indexof/)(IMathElement) | int | Determines the index of a specific math element in collection. |
| [insert](/php-java/mathblock/insert/)(int, IMathElement) | void | Inserts a MathElement into the collection at the specified index. |
| [isReadOnly](/php-java/mathblock/isreadonly/)() | boolean | Returns false because child elements collection can be modified. |
| [iterator](/php-java/mathblock/iterator/)() | IGenericEnumerator | Returns an enumerator that iterates through the collection. |
| [iteratorJava](/php-java/mathblock/iteratorjava/)() | IEnumerator | Returns a java iterator for the entire collection. |
| [join](/php-java/mathblock/join/)(IMathElement) | IMathBlock | Joins a mathematical element with this mathematical block |
| [join](/php-java/mathblock/join/)(String) | IMathBlock | Joins a mathematical text with this mathematical block |
| [joinBlock](/php-java/mathblock/joinblock/)(IMathBlock) | IMathBlock | Joins another mathematical block with this one |
| [remove](/php-java/mathblock/remove/)(IMathElement) | boolean | Removes the first occurrence of a specific object from the collection. |
| [removeAt](/php-java/mathblock/removeat/)(int) | void | Removes the element at the specified index of the collection. |
| [set_Item](/php-java/mathblock/set_item/)(int, IMathElement) | void | Gets or sets IMathElement at the specified index. |
| [toMathArray](/php-java/mathblock/tomatharray/)() | IMathArray | Puts child elements in a vertical array |
| [writeAsMathMl](/php-java/mathblock/writeasmathml/)(OutputStream) | void | Saves content of this MathBlock as MathML |
