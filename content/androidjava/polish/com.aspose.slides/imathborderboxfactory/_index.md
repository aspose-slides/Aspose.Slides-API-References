---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Umożliwia tworzenie ramki granicznej matematycznej
type: docs
url: /pl/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Umożliwia tworzenie ramki granicznej matematycznej

--------------------

Dla porównywalności COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Utwórz ramkę graniczną matematyczną, stosując do elementu |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Utwórz ramkę graniczną matematyczną, stosując do elementu |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Utwórz ramkę graniczną matematyczną, stosując do elementu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego ma być zastosowana ramka graniczna |

**Zwraca:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nowy element ramki granicznej
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Utwórz ramkę graniczną matematyczną, stosując do elementu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego ma być zastosowana ramka graniczna |
| hideTop | boolean | Ukryj górną krawędź |
| hideBottom | boolean | Ukryj dolną krawędź |
| hideLeft | boolean | Ukryj lewą krawędź |
| hideRight | boolean | Ukryj prawą krawędź |
| strikethroughHorizontal | boolean | Przekreślenie poziome w ramce granicznej |
| strikethroughVertical | boolean | Przekreślenie pionowe w ramce granicznej |
| strikethroughBottomLeftToTopRight | boolean | Przekreślenie od dolnego lewego do górnego prawego |
| strikethroughTopLeftToBottomRight | boolean | Przekreślenie od górnego lewego do dolnego prawego |

**Zwraca:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nowy element ramki granicznej