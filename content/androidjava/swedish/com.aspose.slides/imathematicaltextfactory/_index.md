---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /sv/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Tillåter att skapa ett MathematicalText-element

--------------------

För COM-kompatibilitet
## Metoder

| Method | Description |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Create empty mathematical text element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Create mathematical text element with the specified value |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Create empty mathematical text element with the specified value |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create empty mathematical text element with the specified value and formatting properties |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


Skapa ett tomt matematiskt text-element

**Returnerar:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


Skapa ett matematiskt text-element med det angivna värdet

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char | enstaka symbol att använda som textvärde |

**Returnerar:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


Skapa ett tomt matematiskt text-element med det angivna värdet

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | textvärde |

**Returnerar:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Skapa ett tomt matematiskt text-element med det angivna värdet och formateringsinställningarna

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | textvärde |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | inställningar för textformat |

**Returnerar:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text