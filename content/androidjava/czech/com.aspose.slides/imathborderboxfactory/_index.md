---
title: IMathBorderBoxFactory
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Umožňuje vytvořit matematické ohraničovací pole
type: docs
url: /cs/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Umožňuje vytvořit matematické ohraničovací pole

--------------------

Pro kompatibilitu s COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Vytvoří matematické ohraničovací pole aplikací na prvek |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Vytvoří matematické ohraničovací pole aplikací na prvek |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Vytvoří matematické ohraničovací pole aplikací na prvek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek pro aplikaci ohraničovacího pole |

**Vrací:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nový prvek ohraničovacího pole
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Vytvoří matematické ohraničovací pole aplikací na prvek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek pro aplikaci ohraničovacího pole |
| hideTop | boolean | Skrýt horní okraj |
| hideBottom | boolean | Skrýt spodní okraj |
| hideLeft | boolean | Skrýt levý okraj |
| hideRight | boolean | Skrýt pravý okraj |
| strikethroughHorizontal | boolean | Přeškrtnutí ohraničovacího pole vodorovně |
| strikethroughVertical | boolean | Přeškrtnutí ohraničovacího pole svisle |
| strikethroughBottomLeftToTopRight | boolean | Přeškrtnutí ohraničovacího pole od levého dolního k pravému hornímu |
| strikethroughTopLeftToBottomRight | boolean | Přeškrtnutí ohraničovacího pole od levého horního k pravému dolnímu |

**Vrací:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nový prvek ohraničovacího pole