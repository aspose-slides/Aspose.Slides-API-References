---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math delimiter
type: docs
url: /pl/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Umożliwia tworzenie separatora matematycznego

--------------------

Dla zgodności z COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Create a math delimiter by applying to the element |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Create a math delimiter by applying to the element |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

Utwórz separator matematyczny stosując do elementu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego zastosować separator |

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - nowy separator matematyczny
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

Utwórz separator matematyczny stosując do elementu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | elementy matematyczne, do których zastosować separator |

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - nowy separator matematyczny