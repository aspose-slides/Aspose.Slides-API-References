---
title: IMathBlock
second_title: Aspose.Slides pro Android prostřednictvím Java API reference
description: Specifikuje instanci matematického textu, která je obsažena v MathParagraph a začíná na vlastní řádce.
type: docs
url: /cs/com.aspose.slides/imathblock/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Specifikuje instanci matematického textu, která je obsažena v MathParagraph a začíná na vlastní řádce. Všechny matematické oblasti, včetně rovnic, výrazů, polí rovnic nebo výrazů a vzorců, jsou reprezentovány matematickým blokem.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## Metody

| Metoda | Popis |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Odděluje všechny podřízené prvky pomocí znaku oddělovače (bez závorek) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Obaluje podřízené prvky tohoto bloku ve specifikovaných znacích, jako jsou závorky nebo jiné znaky, a odděluje je znakem oddělovače |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Spojuje další matematický blok s tímto |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Ukládá obsah tohoto [IMathBlock](../../com.aspose.slides/imathblock) jako MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Odděluje všechny podřízené prvky pomocí znaku oddělovače (bez závorek)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| separatorCharacter | char | Znak použitý jako oddělovač |

**Vrací:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Instance prvku IMathDelimiter
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Obaluje podřízené prvky tohoto bloku ve specifikovaných znacích, jako jsou závorky nebo jiné znaky, a odděluje je znakem oddělovače

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| beginningCharacter | char | Počáteční znak (obvykle levá závorka) |
| endingCharacter | char | Koncový znak (obvykle pravá závorka) |
| separatorCharacter | char | Znak oddělovače |

**Vrací:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Matematický prvek typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) zahrnující specifikované znaky jako rámeček a oddělovač
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

Spojuje další matematický blok s tímto

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Spojující blok |

**Vrací:**
[IMathBlock](../../com.aspose.slides/imathblock) - tento matematický blok po sloučení
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Ukládá obsah tohoto [IMathBlock](../../com.aspose.slides/imathblock) jako MathML

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Cílový proud |