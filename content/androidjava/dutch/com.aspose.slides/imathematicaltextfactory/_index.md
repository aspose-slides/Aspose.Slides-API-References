---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Staat toe een MathematicalText-element te maken
type: docs
url: /nl/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Staat toe een MathematicalText-element te maken

--------------------

Voor COM-compatibiliteit
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Maak een leeg MathematicalText-element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Maak een MathematicalText-element met de opgegeven waarde |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Maak een leeg MathematicalText-element met de opgegeven waarde |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Maak een leeg MathematicalText-element met de opgegeven waarde en opmaakeigenschappen |
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
| mathSymbol | char | enkel symbool om als tekstwaarde te gebruiken |

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