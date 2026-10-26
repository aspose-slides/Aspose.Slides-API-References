---
title: MathematicalTextFactory
second_title: Aspose.Slides a Java API hivatkozás
description: Lehetővé teszi egy MathematicalText elem létrehozását
type: docs
url: /hu/com.aspose.slides/mathematicaltextfactory/
---
**Öröklés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

Lehetővé teszi egy MathematicalText elem létrehozását

--------------------

COM kompatibilitáshoz
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Create empty mathematical text element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Create mathematical text element with the specified value |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Create empty mathematical text element with the specified value |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create empty mathematical text element with the specified value and formatting properties |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```

### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```

Üres matematikai szövegelem hoz létre

**Visszatérési érték:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - új Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```

Matematikai szövegelem létrehozása a megadott értékkel

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathSymbol | char | egyetlen szimbólum a szövegértékhez |

**Visszatérési érték:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - új Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```

Üres matematikai szövegelem létrehozása a megadott értékkel

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | java.lang.String | szövegérték |

**Visszatérési érték:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - új Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Üres matematikai szövegelem létrehozása a megadott értékkel és formázási beállításokkal

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | java.lang.String | szövegérték |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | szövegformátum beállítások |

**Visszatérési érték:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - új Mathematical Text