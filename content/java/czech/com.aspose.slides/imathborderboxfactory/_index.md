---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math border box
type: docs
url: /cs/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Umožňuje vytvořit matematický border box

--------------------

Pro kompatibilitu s COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Vytvoří math border box aplikací na prvek |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Vytvoří math border box aplikací na prvek |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Vytvoří math border box aplikací na prvek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek, na který se má aplikovat border box |

**Vrací:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) – nový border box element
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Vytvoří math border box aplikací na prvek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek, na který se má aplikovat border box |
| hideTop | boolean | Skrýt horní okraj |
| hideBottom | boolean | Skrýt spodní okraj |
| hideLeft | boolean | Skrýt levý okraj |
| hideRight | boolean | Skrýt pravý okraj |
| strikethroughHorizontal | boolean | Border Box přeškrtnutí vodorovně |
| strikethroughVertical | boolean | Border Box přeškrtnutí svisle |
| strikethroughBottomLeftToTopRight | boolean | Border Box přeškrtnutí z levého dolního rohu k pravému hornímu |
| strikethroughTopLeftToBottomRight | boolean | Border Box přeškrtnutí z levého horního rohu k pravému dolnímu |

**Vrací:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) – nový border box element