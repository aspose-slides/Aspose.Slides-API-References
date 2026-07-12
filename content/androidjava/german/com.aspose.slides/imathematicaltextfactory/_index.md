---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /de/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Ermöglicht das Erstellen eines MathematicalText-Elements

--------------------

Für COM-Kompatibilität
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Create empty mathematical text element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Create mathematical text element with the specified value |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Create empty mathematical text element with the specified value |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create empty mathematical text element with the specified value and formatting properties |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

Erstelle ein leeres MathematicalText-Element

**Rückgabewert:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - neues Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

Erstelle ein MathematicalText-Element mit dem angegebenen Wert

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathSymbol | char | einzelnes Symbol, das als Textwert verwendet wird |

**Rückgabewert:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - neues Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

Erstelle ein leeres MathematicalText-Element mit dem angegebenen Wert

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathText | java.lang.String | Textwert |

**Rückgabewert:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - neues Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Erstelle ein leeres MathematicalText-Element mit dem angegebenen Wert und Formatierungseigenschaften

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathText | java.lang.String | Textwert |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | Texteinstellungen |

**Rückgabewert:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - neues Mathematical Text