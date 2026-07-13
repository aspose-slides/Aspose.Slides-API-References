---
title: MathematicalTextFactory
second_title: Aspose.Slides voor Android via Java API-referentie
description: Staat toe een MathematicalText element te maken
type: docs
url: /nl/com.aspose.slides/mathematicaltextfactory/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

Staat toe een MathematicalText-element te maken

--------------------

Voor COM-compatibiliteit
## Constructeurs

| Constructor | Omschrijving |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## Methoden

| Method | Omschrijving |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Maak leeg wiskundig tekstelement |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Maak wiskundig tekstelement met de opgegeven waarde |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Maak leeg wiskundig tekstelement met de opgegeven waarde |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Maak leeg wiskundig tekstelement met de opgegeven waarde en opmaak-eigenschappen |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```


### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```


Maak leeg wiskundig tekstelement

**Retour:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```


Maak wiskundig tekstelement met de opgegeven waarde

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| mathSymbol | char | enkel symbool dat als tekstwaarde wordt gebruikt |

**Retour:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```


Maak leeg wiskundig tekstelement met de opgegeven waarde

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| mathText | java.lang.String | tekstwaarde |

**Retour:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Maak leeg wiskundig tekstelement met de opgegeven waarde en opmaak-eigenschappen

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| mathText | java.lang.String | tekstwaarde |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | tekst-opmaakinstellingen |

**Retour:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text