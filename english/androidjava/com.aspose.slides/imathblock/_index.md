---
title: IMathBlock
second_title: Aspose.Slides for Android via Java API Reference
description: Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line.
type: docs
weight: 888
url: /androidjava/com.aspose.slides/imathblock/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Specifies an instance of mathematical text that contained within a MathParagraph and starts on its own line. All math zones, including equations, expressions, arrays of equations or expressions, and formulas are represented by math block.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```
## Methods

| Method | Description |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Delimits all child elements with separator character (without the brackets) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Encloses child elements of this block in specified characters such as parenthesis or another as framing and delimit with a separator character |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Joins another mathematical block with this one |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Saves content of this [IMathBlock](../../com.aspose.slides/imathblock) as MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```


Delimits all child elements with separator character (without the brackets)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| separatorCharacter | char | Character used as a separator |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Instance of IMathDelimiter element
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```


Encloses child elements of this block in specified characters such as parenthesis or another as framing and delimit with a separator character

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char | Beginning character (usually left bracket) |
| endingCharacter | char | Ending character (usually right bracket) |
| separatorCharacter | char | Separator character |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - The math element of type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) which includes specified characters as framing and delimiter
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```


Joins another mathematical block with this one

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | The joining block |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - this mathematical block after joining
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


Saves content of this [IMathBlock](../../com.aspose.slides/imathblock) as MathML

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |

