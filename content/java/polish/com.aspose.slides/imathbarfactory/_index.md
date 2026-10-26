---
title: IMathBarFactory
second_title: Aspose.Slides for Java API Reference
description: Umożliwia tworzenie paska matematycznego
type: docs
url: /pl/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

Umożliwia tworzenie paska matematycznego

--------------------

Dla zgodności z COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Utwórz pasek matematyczny, stosując go do elementu |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Utwórz pasek matematyczny, stosując go do elementu |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```


Utwórz pasek matematyczny, stosując go do elementu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego zastosować pasek |

**Zwraca:**
[IMathBar](../../com.aspose.slides/imathbar) - nowy element paska matematycznego
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```


Utwórz pasek matematyczny, stosując go do elementu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Element matematyczny, do którego zastosować pasek |
| position | int | Pozycja paska |

**Zwraca:**
[IMathBar](../../com.aspose.slides/imathbar) - nowy element paska matematycznego