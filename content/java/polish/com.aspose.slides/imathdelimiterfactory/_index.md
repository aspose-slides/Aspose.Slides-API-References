---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Java API Reference
description: Umożliwia utworzenie separatora matematycznego
type: docs
url: /pl/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Umożliwia utworzenie separatora matematycznego

--------------------

Dla zgodności z COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Utwórz separator matematyczny, stosując go do elementu |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Utwórz separator matematyczny, stosując go do elementu |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

Utwórz separator matematyczny, stosując go do elementu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, któremu ma zostać zastosowany separator |

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - nowy separator matematyczny
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

Utwórz separator matematyczny, stosując go do elementu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | elementy matematyczne, którym ma zostać zastosowany separator |

**Zwraca:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - nowy separator matematyczny