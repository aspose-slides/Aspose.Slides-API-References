---
title: MathBorderBoxFactory
second_title: Aspose.Slides dla Java – dokumentacja API
description: Umożliwia utworzenie ramki obramowania matematycznego
type: docs
url: /pl/com.aspose.slides/mathborderboxfactory/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Umożliwia utworzenie ramki obramowania matematycznego

--------------------

Dla zgodności z COM
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Utwórz ramkę obramowania matematycznego, stosując do elementu |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Utwórz ramkę obramowania matematycznego, stosując do elementu |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


Utwórz ramkę obramowania matematycznego, stosując do elementu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego zastosować ramkę obramowania |

**Zwraca:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nowy element ramki obramowania
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Utwórz ramkę obramowania matematycznego, stosując do elementu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego zastosować ramkę obramowania |
| hideTop | boolean | Ukryj górną krawędź |
| hideBottom | boolean | Ukryj dolną krawędź |
| hideLeft | boolean | Ukryj lewą krawędź |
| hideRight | boolean | Ukryj prawą krawędź |
| strikethroughHorizontal | boolean | Przekreślenie poziome ramki obramowania |
| strikethroughVertical | boolean | Przekreślenie pionowe ramki obramowania |
| strikethroughBottomLeftToTopRight | boolean | Przekreślenie od dolnego lewego do górnego prawego w ramce obramowania |
| strikethroughTopLeftToBottomRight | boolean | Przekreślenie od górnego lewego do dolnego prawego w ramce obramowania |

**Zwraca:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nowy element ramki obramowania