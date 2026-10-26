---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Lehetővé teszi egy MathematicalText elem létrehozását
type: docs
url: /hu/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Lehetővé teszi egy MathematicalText elem létrehozását

--------------------

COM kompatibilitás miatt
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Üres matematikai szövegelem létrehozása |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Matematikai szövegelem létrehozása a megadott értékkel |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Üres matematikai szövegelem létrehozása a megadott értékkel |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Üres matematikai szövegelem létrehozása a megadott értékkel és formázási tulajdonságokkal |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

Üres matematikai szövegelem létrehozása

**Visszatér:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - új Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

Matematikai szövegelem létrehozása a megadott értékkel

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathSymbol | char | az értékként használandó egyetlen szimbólum |

**Visszatér:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - új Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

Üres matematikai szövegelem létrehozása a megadott értékkel

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | java.lang.String | szöveges érték |

**Visszatér:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - új Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Üres matematikai szövegelem létrehozása a megadott értékkel és formázási tulajdonságokkal

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | java.lang.String | szöveges érték |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | szövegformázási beállítások |

**Visszatér:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - új Mathematical Text