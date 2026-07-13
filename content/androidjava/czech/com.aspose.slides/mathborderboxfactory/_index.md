---
title: MathBorderBoxFactory
second_title: Aspose.Slides pro Android přes Java API referenci
description: Umožňuje vytvořit matematické ohraničovací pole
type: docs
url: /cs/com.aspose.slides/mathborderboxfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Umožňuje vytvořit matematické ohraničovací pole

--------------------

Pro kompatibilitu s COM
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
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek pro aplikaci ohraničovacího pole |

**Vrací:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) – nový prvek ohraničovacího pole
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Vytvoří matematické ohraničovací pole aplikací na prvek

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | matematický prvek pro aplikaci ohraničovacího pole |
| hideTop | boolean | Skrýt horní okraj |
| hideBottom | boolean | Skrýt dolní okraj |
| hideLeft | boolean | Skrýt levý okraj |
| hideRight | boolean | Skrýt pravý okraj |
| strikethroughHorizontal | boolean | Vodorovné přeškrtnutí rámečku |
| strikethroughVertical | boolean | Svislé přeškrtnutí rámečku |
| strikethroughBottomLeftToTopRight | boolean | Přeškrtnutí rámečku z levého dolního do pravého horního rohu |
| strikethroughTopLeftToBottomRight | boolean | Přeškrtnutí rámečku z levého horního do pravého dolního rohu |

**Vrací:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) – nový prvek ohraničovacího pole