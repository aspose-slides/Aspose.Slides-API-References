---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java API Reference
description: Erlaubt das Erstellen eines MathematicalText-Elements
type: docs
url: /de/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Erlaubt das Erstellen eines MathematicalText-Elements

--------------------

Für COM-Kompatibilität
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Erstelle leeres MathematicalText-Element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Erstelle MathematicalText-Element mit dem angegebenen Wert |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Erstelle leeres MathematicalText-Element mit dem angegebenen Wert |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Erstelle leeres MathematicalText-Element mit dem angegebenen Wert und Formatierungseigenschaften |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

Erstelle leeres MathematicalText-Element

**Rückgabewert:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

Erstelle MathematicalText-Element mit dem angegebenen Wert

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathSymbol | char | einzelnes Symbol, das als Textwert verwendet wird |

**Rückgabewert:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

Erstelle leeres MathematicalText-Element mit dem angegebenen Wert

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathText | java.lang.String | Textwert |

**Rückgabewert:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Erstelle leeres MathematicalText-Element mit dem angegebenen Wert und Formatierungseigenschaften

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathText | java.lang.String | Textwert |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | Texteinstellungen |

**Rückgabewert:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text