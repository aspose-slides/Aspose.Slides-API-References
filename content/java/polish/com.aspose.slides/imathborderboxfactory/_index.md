---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Reference
description: Umożliwia tworzenie obramowania matematycznego
type: docs
url: /pl/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Umożliwia tworzenie obramowania matematycznego

--------------------

Dla kompatybilności z COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Create a math border box by applying to the element |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Create a math border box by applying to the element |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Utwórz obramowanie matematyczne, stosując do elementu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply border box |

**Zwraca:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nowy element obramowania
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Utwórz obramowanie matematyczne, stosując do elementu

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply border box |
| hideTop | boolean | Ukryj górną krawędź |
| hideBottom | boolean | Ukryj dolną krawędź |
| hideLeft | boolean | Ukryj lewą krawędź |
| hideRight | boolean | Ukryj prawą krawędź |
| strikethroughHorizontal | boolean | Przekreślenie poziome obramowania |
| strikethroughVertical | boolean | Przekreślenie pionowe obramowania |
| strikethroughBottomLeftToTopRight | boolean | Przekreślenie od dolnego-lewego do górnego-prawego |
| strikethroughTopLeftToBottomRight | boolean | Przekreślenie od górnego-lewego do dolnego-prawego |

**Zwraca:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nowy element obramowania