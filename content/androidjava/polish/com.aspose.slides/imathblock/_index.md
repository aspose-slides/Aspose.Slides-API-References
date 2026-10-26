---
title: IMathBlock
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Określa instancję tekstu matematycznego, który znajduje się w obrębie MathParagraph i rozpoczyna się w osobnej linii.
type: docs
url: /pl/com.aspose.slides/imathblock/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Określa instancję tekstu matematycznego, który znajduje się w obrębie MathParagraph i rozpoczyna się w osobnej linii. Wszystkie strefy matematyczne, w tym równania, wyrażenia, tablice równań lub wyrażeń oraz formuły, są reprezentowane przez blok matematyczny.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## Metody

| Metoda | Opis |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Oddziela wszystkie elementy potomne znakiem separatora (bez nawiasów) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | Otacza elementy potomne tego bloku określonymi znakami, takimi jak nawiasy lub inne, jako ramka i oddziela je znakiem separatora |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Łączy inny blok matematyczny z tym |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | Zapisuje zawartość tego [IMathBlock](../../com.aspose.slides/imathblock) jako MathML |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```


Oddziela wszystkie elementy potomne znakiem separatora (bez nawiasów)

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| separatorCharacter | char | Znak używany jako separator |

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Instancja elementu IMathDelimiter
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```


Otacza elementy potomne tego bloku określonymi znakami, takimi jak nawiasy lub inne, jako ramka i oddziela je znakiem separatora

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| beginningCharacter | char | Znak początkowy (zwykle lewy nawias) |
| endingCharacter | char | Znak końcowy (zwykle prawy nawias) |
| separatorCharacter | char | Znak separatora |

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Element matematyczny typu [IMathDelimiter](../../com.aspose.slides/imathdelimiter) zawierający określone znaki jako ramkę i separator
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```


Łączy inny blok matematyczny z tym

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | Blok łączący |

**Zwraca:**
[IMathBlock](../../com.aspose.slides/imathblock) - ten blok matematyczny po połączeniu
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


Zapisuje zawartość tego [IMathBlock](../../com.aspose.slides/imathblock) jako MathML

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.OutputStream | Strumień docelowy |