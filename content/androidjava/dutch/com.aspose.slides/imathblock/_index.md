---
title: IMathBlock
second_title: Aspose.Slides voor Android via Java API-referentie
description: Specificeert een instantie van wiskundige tekst die zich bevindt binnen een MathParagraph en op een eigen regel begint.
type: docs
url: /nl/com.aspose.slides/imathblock/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Specificeert een instantie van wiskundige tekst die zich bevindt binnen een MathParagraph en op een eigen regel begint. Alle wiskundige zones, inclusief vergelijkingen, expressies, reeksen van vergelijkingen of expressies, en formules worden weergegeven door een math block.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Scheidt alle onderliggende elementen met scheidingsteken (zonder de haakjes) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Omvat onderliggende elementen van dit blok in opgegeven tekens, zoals haakjes of andere, als omlijsting en scheidt met een scheidingsteken |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Voegt een ander wiskundig blok samen met dit blok |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Slaat de inhoud van deze [IMathBlock](../../com.aspose.slides/imathblock) op als MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Scheidt alle onderliggende elementen met scheidingsteken (zonder de haakjes)

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
| separatorCharacter | char | Teken dat als scheidingsteken wordt gebruikt |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Instance van IMathDelimiter element
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

Omvat onderliggende elementen van dit blok in opgegeven tekens, zoals haakjes of andere, als omlijsting en scheidt met een scheidingsteken

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
| beginningCharacter | char | Beginteken (meestal linkere haak) |
| endingCharacter | char | Eindteken (meestal rechter haak) |
| separatorCharacter | char | Scheidingsteken |

**Returns:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Het wiskunde-element van type [IMathDelimiter](../../com.aspose.slides/imathdelimiter) dat opgegeven tekens als omlijsting en scheidingsteken bevat
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

Voegt een ander wiskundig blok samen met dit blok

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
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Het te voegen blok |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - dit wiskundige blok na het samenvoegen
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

Slaat de inhoud van deze [IMathBlock](../../com.aspose.slides/imathblock) op als MathML

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Doelstream |