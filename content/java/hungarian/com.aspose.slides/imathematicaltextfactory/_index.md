---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /hu/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Lehetővé teszi egy MathematicalText elem létrehozását

--------------------

COM kompatibilitás miatt
## Módszerek

| Method | Description |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Üres MathematicalText elemet hoz létre |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | MathematicalText elemet hoz létre a megadott értékkel |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Üres MathematicalText elemet hoz létre a megadott értékkel |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Üres MathematicalText elemet hoz létre a megadott értékkel és formázási tulajdonságokkal |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


Üres MathematicalText elemet hoz létre

**Visszatérési érték:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - új Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


MathematicalText elemet hoz létre a megadott értékkel

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathSymbol | char | a szöveges értékhez használandó egyetlen szimbólum |

**Visszatérési érték:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - új Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


Üres MathematicalText elemet hoz létre a megadott értékkel

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | java.lang.String | szöveges érték |

**Visszatérési érték:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - új Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Üres MathematicalText elemet hoz létre a megadott értékkel és formázási tulajdonságokkal

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | java.lang.String | szöveges érték |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | szövegformázási beállítások |

**Visszatérési érték:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - új Mathematical Text