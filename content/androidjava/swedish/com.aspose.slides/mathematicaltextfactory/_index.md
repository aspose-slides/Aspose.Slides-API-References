---
title: MathematicalTextFactory
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att skapa ett MathematicalText-element
type: docs
url: /sv/com.aspose.slides/mathematicaltextfactory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

Tillåter att skapa ett MathematicalText element

--------------------

För COM-kompatibilitet
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Skapa tomt MathematicalText element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Skapa ett MathematicalText element med det angivna värdet |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Skapa tomt MathematicalText element med det angivna värdet |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Skapa tomt MathematicalText element med det angivna värdet och formateringsinställningar |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```


### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```


Skapa tomt MathematicalText element

**Returnerar:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```


Skapa ett MathematicalText element med det angivna värdet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathSymbol | char | en enda symbol att använda som textvärde |

**Returnerar:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```


Skapa tomt MathematicalText element med det angivna värdet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathText | java.lang.String | textvärde |

**Returnerar:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Skapa tomt MathematicalText element med det angivna värdet och formateringsinställningar

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathText | java.lang.String | textvärde |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | inställningar för textformat |

**Returnerar:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text