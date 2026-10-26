---
title: IMathBlock
second_title: Aspose.Slides voor Java API-referentie
description: Specificeert een instantie van wiskundige tekst die zich bevindt binnen een MathParagraph en op een eigen regel begint.
type: docs
url: /nl/com.aspose.slides/imathblock/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Specificeert een instantie van wiskundige tekst die zich bevindt binnen een MathParagraph en op een eigen regel begint. Alle wiskunde-gebieden, inclusief vergelijkingen, expressies, rijen van vergelijkingen of expressies, en formules worden weergegeven door een wiskundig blok.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Begrens alle onderliggende elementen met scheidingsteken (zonder de haakjes) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Omhult onderliggende elementen van dit blok met gespecificeerde tekens zoals haakjes of andere als omlijsting en begrenst met een scheidingsteken |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Voegt een ander wiskundig blok toe aan dit blok |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Slaat de inhoud van deze [IMathBlock](../../com.aspose.slides/imathblock) op als MathML |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Begrens alle onderliggende elementen met scheidingsteken (zonder de haakjes)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| separatorCharacter | char | Teken dat wordt gebruikt als scheidingsteken |

**Retourwaarde:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Instantie van IMathDelimiter-element

### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Omhult onderliggende elementen van dit blok met gespecificeerde tekens zoals haakjes of andere als omlijsting en begrenst met een scheidingsteken

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| beginningCharacter | char | Beginteken (meestal linker haakje) |
| endingCharacter | char | Eindteken (meestal rechter haakje) |
| separatorCharacter | char | Scheidingsteken |

**Retourwaarde:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Het wiskunde-element van type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) dat gespecificeerde tekens als omlijsting en scheidingsteken bevat

### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

Voegt een ander wiskundig blok toe aan dit blok

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Het samenvoegende blok |

**Retourwaarde:**
[IMathBlock](../../com.aspose.slides/imathblock) - dit wiskundige blok na samenvoegen

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Slaat de inhoud van deze [IMathBlock](../../com.aspose.slides/imathblock) op als MathML

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doelstream |