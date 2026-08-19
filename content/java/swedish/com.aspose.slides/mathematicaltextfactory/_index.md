---
title: MathematicalTextFactory
second_title: Aspose.Slides för Java API-referens
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

Tillåter att skapa ett MathematicalText-element

--------------------

För COM-kompatibilitet
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Skapa tomt matematiskt textelement |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Skapa matematiskt textelement med det angivna värdet |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Skapa tomt matematiskt textelement med det angivna värdet |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Skapa tomt matematiskt textelement med det angivna värdet och formateringsegenskaper |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```


### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```


Skapa tomt matematiskt textelement

**Returnerar:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - ny Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```


Skapa matematiskt textelement med det angivna värdet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathSymbol | char | enstaka symbol att använda som textevärde |

**Returnerar:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - ny Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```


Skapa tomt matematiskt textelement med det angivna värdet

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathText | java.lang.String | textevärde |

**Returnerar:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - ny Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Skapa tomt matematiskt textelement med det angivna värdet och formateringsegenskaper

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mathText | java.lang.String | textevärde |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | textformatinställningar |

**Returnerar:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - ny Mathematical Text