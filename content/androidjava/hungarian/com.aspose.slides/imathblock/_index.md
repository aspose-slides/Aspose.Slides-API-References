---
title: IMathBlock
second_title: Aspose.Slides for Android Java API hivatkozás
description: Megad egy matematikai szöveg példányt, amely egy MathParagraph-on belül található és saját sorban kezdődik.
type: docs
url: /hu/com.aspose.slides/imathblock/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IMathElementCollection](../../com.aspose.slides/imathelementcollection), [com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBlock extends IMathElementCollection, IMathElement
```

Megad egy matematikai szöveg példányt, amely egy MathParagraph-on belül található és saját sorban kezdődik. Az összes matematikai zóna, beleértve az egyenleteket, kifejezéseket, egyenletekből vagy kifejezésekből álló tömböket és képleteket, egy matematikai blokk által van reprezentálva.

--------------------

> ```
> Example:
>  
>  IMathBlock mathBlock = new MathBlock();
> ```
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [delimit(char separatorCharacter)](#delimit-char-) | Elválasztja az összes gyermekelemet a megadott elválasztó karakterrel (a zárójelek nélkül) |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | A blokk gyermekelemeit a megadott karakterekkel (például zárójelek vagy más keretező karakterek) veszi körül, és elválasztja őket egy elválasztó karakterrel |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | Egy másik matematikai blokkot csatlakoztat ehhez |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | A [IMathBlock](../../com.aspose.slides/imathblock) tartalmát MathML-ként menti |
### delimit(char separatorCharacter) {#delimit-char-}
```
public abstract IMathDelimiter delimit(char separatorCharacter)
```


Elválasztja az összes gyermekelemet a megadott elválasztó karakterrel (a zárójelek nélkül)

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
| separatorCharacter | char | Elválasztóként használt karakter |

**Visszatérési érték:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Az IMathDelimiter elem példánya
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public abstract IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```


A blokk gyermekelemeit a megadott karakterekkel (például zárójelek vagy más keretező karakterek) veszi körül, és elválasztja őket egy elválasztó karakterrel

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
| beginningCharacter | char | Kezdő karakter (általában bal zárójel) |
| endingCharacter | char | Záró karakter (általában jobb zárójel) |
| separatorCharacter | char | Elválasztó karakter |

**Visszatérési érték:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - A [IMathDelimiter](../../com.aspose.slides/imathdelimiter) típusú matematikai elem, amely a megadott karaktereket keretként és elválasztóként tartalmazza
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public abstract IMathBlock joinBlock(IMathBlock other)
```


Egy másik matematikai blokkot csatlakoztat ehhez

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
| other | [IMathBlock](../../com.aspose.slides/imathblock) | A csatlakoztatandó blokk |

**Visszatérési érték:**
[IMathBlock](../../com.aspose.slides/imathblock) - ez a matematikai blokk a csatlakoztatás után
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public abstract void writeAsMathMl(OutputStream stream)
```


[IMathBlock](../../com.aspose.slides/imathblock) tartalmát MathML-ként menti

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Célfolyam |