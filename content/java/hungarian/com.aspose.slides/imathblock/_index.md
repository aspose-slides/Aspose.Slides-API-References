---
title: IMathBlock
second_title: Aspose.Slides for Java API referencia
description: Megad egy olyan matematikai szöveg példányt, amely egy MathParagraph-ban található, és saját sorban kezdődik.
type: docs
url: /hu/com.aspose.slides/imathblock/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Meghatároz egy matematikai szövegpéldányt, amely egy MathParagraph-ban található, és saját sorban kezdődik. Az összes matematikai zóna, beleértve az egyenleteket, kifejezéseket, egyenletekből vagy kifejezésekből álló tömböket, valamint a képleteket, a math block által van ábrázolva.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Határolja le az összes gyermekelemet a szeparátor karakterrel (a zárójelek nélkül) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | A blokk gyermekelemeit a megadott karakterekkel, például zárójelekkel vagy más kerettel veszi körül, és a szeparátor karakterrel határolja |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Egy másik matematikai blokkot csatlakoztat ehhez |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | A [IMathBlock](../../com.aspose.slides/imathblock) tartalmát MathML-ként menti |

### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```

Határolja le az összes gyermekelemet a szeparátor karakterrel (a zárójelek nélkül).

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separatorCharacter | char | A szeparátorként használt karakter |

**Visszatér:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Az IMathDelimiter elem példánya

### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

A blokk gyermekelemeit megadott karakterekkel, például zárójelekkel vagy más kerettel veszi körül, és szeparátor karakterrel határolja.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| beginningCharacter | char | A kezdő karakter (általában bal zárójel) |
| endingCharacter | char | A befejező karakter (általában jobb zárójel) |
| separatorCharacter | char | Szeparátor karakter |

**Visszatér:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - A [IMathDelimiter](../../com.aspose.slides/imathdelimiter) típusú matematikai elem, amely a megadott karaktereket keretként és határolóként tartalmazza

### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```

Egy másik matematikai blokkot csatlakoztat ehhez.

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | A csatlakozó blokk |

**Visszatér:**
[IMathBlock](../../com.aspose.slides/imathblock) - ez a matematikai blokk a csatlakoztatás után

### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```

A [IMathBlock](../../com.aspose.slides/imathblock) tartalmát MathML-ként menti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Célfolyam |