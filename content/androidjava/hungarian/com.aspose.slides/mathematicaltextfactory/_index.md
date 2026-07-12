---
title: MathematicalTextFactory
second_title: Aspose.Slides for Android Java API referencia
description: Lehetővé teszi egy MathematicalText elem létrehozását
type: docs
url: /hu/com.aspose.slides/mathematicaltextfactory/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
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
| [createMathematicalText()](#createMathematicalText--) | Üres matematikai szöveg elemet hoz létre |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Matematikai szöveg elemet hoz létre a megadott értékkel |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Üres matematikai szöveg elemet hoz létre a megadott értékkel |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Üres matematikai szöveg elemet hoz létre a megadott értékkel és formázási tulajdonságokkal |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```


### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```


Üres matematikai szöveg elemet hoz létre

**Visszatérési érték:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - új Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```


Matematikai szöveg elemet hoz létre a megadott értékkel

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathSymbol | char | egyes szimbólum, amely szöveges értékként használható |

**Visszatérési érték:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - új Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```


Üres matematikai szöveg elem a megadott értékkel

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | java.lang.String | szöveges érték |

**Visszatérési érték:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - új Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Üres matematikai szöveg elemet hoz létre a megadott értékkel és formázási tulajdonságokkal

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | java.lang.String | szöveges érték |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | szövegformázási beállítások |

**Visszatérési érték:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - új Mathematical Text