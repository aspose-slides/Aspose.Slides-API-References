---
title: IMathBlock
second_title: Aspose.Slides för Android via Java API-referens
description: Specificerar en instans av matematisk text som finns i ett MathParagraph och börjar på en egen rad.
type: docs
url: /sv/com.aspose.slides/imathblock/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Specificerar en instans av matematisk text som finns inom ett MathParagraph och börjar på en egen rad. Alla matematiska zoner, inklusive ekvationer, uttryck, matriser av ekvationer eller uttryck och formler representeras av math block.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Avgränsar alla underordnade element med separator-tecken (utan hakparenteserna) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Inramar underordnade element i detta block med angivna tecken såsom parenteser eller andra som ram och avgränsar med ett separator-tecken |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Kombinerar ett annat matematiskt block med detta |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Sparar innehållet i detta [IMathBlock](../../com.aspose.slides/imathblock) som MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```


Avgränsar alla underordnade element med separator-tecken (utan hakparenteserna)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separatorCharacter | char | Tecken som används som separator |

**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Instans av IMathDelimiter-element
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```


Inramar underordnade element i detta block med angivna tecken såsom parenteser eller andra som ram och avgränsar med ett separator-tecken

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| beginningCharacter | char | Inledande tecken (vanligtvis vänster hakparentes) |
| endingCharacter | char | Avslutande tecken (vanligtvis höger hakparentes) |
| separatorCharacter | char | Separator-tecken |

**Returnerar:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Math-elementet av typen [IMathDelimiter](../../com.aspose.slides/imathdelimiter) som inkluderar angivna tecken som ram och avgränsare
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```


Kombinerar ett annat matematiskt block med detta

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Det förenande blocket |

**Returnerar:**
[IMathBlock](../../com.aspose.slides/imathblock) - detta matematiska block efter förening
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


Sparar innehållet i detta [IMathBlock](../../com.aspose.slides/imathblock) som MathML

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Målsström |