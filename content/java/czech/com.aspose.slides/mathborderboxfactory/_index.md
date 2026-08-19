---
title: MathBorderBoxFactory
second_title: Aspose.Slides pro Java – referenční příručka API
description: Umožňuje vytvořit matematické ohraničovací pole
type: docs
url: /cs/com.aspose.slides/mathborderboxfactory/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Umožňuje vytvořit matematické ohraničovací pole

--------------------

Pro COM kompatibilitu
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Vytvoří matematické ohraničovací pole aplikací na prvek |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Vytvoří matematické ohraničovací pole aplikací na prvek |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


Vytvoří matematické ohraničovací pole aplikací na prvek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek, na který se aplikuje ohraničovací pole |

**Návratová hodnota:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nový prvek ohraničovacího pole
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Vytvoří matematické ohraničovací pole aplikací na prvek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek, na který se aplikuje ohraničovací pole |
| hideTop | boolean | Skrýt horní okraj |
| hideBottom | boolean | Skrýt spodní okraj |
| hideLeft | boolean | Skrýt levý okraj |
| hideRight | boolean | Skrýt pravý okraj |
| strikethroughHorizontal | boolean | Přeškrtnutí ohraničovacího pole vodorovně |
| strikethroughVertical | boolean | Přeškrtnutí ohraničovacího pole svisle |
| strikethroughBottomLeftToTopRight | boolean | Přeškrtnutí ohraničovacího pole od levého dolního k pravému hornímu |
| strikethroughTopLeftToBottomRight | boolean | Přeškrtnutí ohraničovacího pole od levého horního k pravému dolnímu |

**Návratová hodnota:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nový prvek ohraničovacího pole