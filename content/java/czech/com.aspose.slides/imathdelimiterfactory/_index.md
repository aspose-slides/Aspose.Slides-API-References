---
title: IMathDelimiterFactory
second_title: Aspose.Slides pro Java API Reference
description: Umožňuje vytvořit matematický oddělovač
type: docs
url: /cs/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Umožňuje vytvořit matematický oddělovač

--------------------

Pro kompatibilitu s COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Vytvoří matematický oddělovač aplikací na prvek |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Vytvoří matematický oddělovač aplikací na prvek |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

Vytvoří matematický oddělovač aplikací na prvek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek pro aplikaci oddělovače |

**Návratová hodnota:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - nový matematický oddělovač
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

Vytvoří matematický oddělovač aplikací na prvek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematické prvky pro aplikaci oddělovače |

**Návratová hodnota:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - nový matematický oddělovač