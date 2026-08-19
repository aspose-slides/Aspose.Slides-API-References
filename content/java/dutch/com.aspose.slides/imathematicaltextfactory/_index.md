---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /nl/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Stelt u in staat om een MathematicalText-element te maken

--------------------

Voor COM-compatibiliteit
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Create empty mathematical text element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Create mathematical text element with the specified value |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Create empty mathematical text element with the specified value |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create empty mathematical text element with the specified value and formatting properties |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

Maak een leeg MathematicalText-element

**Retour:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

Maak een MathematicalText-element met de opgegeven waarde

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathSymbol | char | enkel symbool dat als tekstwaarde wordt gebruikt |

**Retour:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

Maak een leeg MathematicalText-element met de opgegeven waarde

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathText | java.lang.String | tekstwaarde |

**Retour:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

Maak een leeg MathematicalText-element met de opgegeven waarde en opmaakeigenschappen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| mathText | java.lang.String | tekstwaarde |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | tekstopmaakinstellingen |

**Retour:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text