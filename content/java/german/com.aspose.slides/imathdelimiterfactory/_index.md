---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Java API Reference
description: Ermöglicht das Erstellen eines mathematischen Trennzeichens
type: docs
url: /de/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Ermöglicht das Erstellen eines mathematischen Trennzeichens

--------------------

Für COM-Kompatibilität
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Erstellt ein mathematisches Trennzeichen, indem es auf das Element angewendet wird |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Erstellt ein mathematisches Trennzeichen, indem es auf das Element angewendet wird |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```


Erstellt ein mathematisches Trennzeichen, indem es auf das Element angewendet wird

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathe-Element, auf das das Trennzeichen angewendet wird |

**Rückgabewert:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - neues mathematisches Trennzeichen
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```


Erstellt ein mathematisches Trennzeichen, indem es auf das Element angewendet wird

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | Mathe-Elemente, auf die das Trennzeichen angewendet wird |

**Rückgabewert:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - neues mathematisches Trennzeichen