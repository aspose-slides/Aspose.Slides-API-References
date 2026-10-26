---
title: IMathBlock
second_title: Aspose.Slides pro Java API Reference
description: Specifikuje instanci matematického textu, která je obsažena v MathParagraph a začíná na samostatném řádku.
type: docs
url: /cs/com.aspose.slides/imathblock/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Specifikuje instanci matematického textu, která je obsažena v MathParagraph a začíná na samostatném řádku. Všechny matematické oblasti, včetně rovnic, výrazů, polí rovnic nebo výrazů a vzorců jsou reprezentovány matematickým blokem.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```
## Methods

| Method | Description |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Odděluje všechny podřízené prvky pomocí oddělovače (bez závorek) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Obalí podřízené prvky tohoto bloku určenými znaky, například závorkami nebo jinými, a oddělí je pomocí oddělovače |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Spojí jiný matematický blok s tímto |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Uloží obsah tohoto [IMathBlock](../../com.aspose.slides/imathblock) jako MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```


Odděluje všechny podřízené prvky pomocí oddělovače (bez závorek)

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
| separatorCharacter | char | Znak použitý jako oddělovač |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Instance elementu IMathDelimiter
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```


Obalí podřízené prvky tohoto bloku určenými znaky, například závorkami nebo jinými, a oddělí je pomocí oddělovače

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
| beginningCharacter | char | Počáteční znak (obvykle levá závorka) |
| endingCharacter | char | Koncový znak (obvykle pravá závorka) |
| separatorCharacter | char | Separator character |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Matematiký prvek typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter), který zahrnuje určené znaky jako ohraničení a oddělovač
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```


Spojí jiný matematický blok s tímto

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
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Spojovací blok |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - tento matematický blok po spojení
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


Uloží obsah tohoto [IMathBlock](../../com.aspose.slides/imathblock) jako MathML

**Parameters:**
| Parameter | Type | Description |
| --- | --- | |
| stream | java.io.OutputStream | Cílový stream |