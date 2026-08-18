---
title: MathBorderBoxFactory
second_title: Aspose.Slides für Java API-Referenz
description: Ermöglicht das Erstellen einer mathematischen Rahmen-Box
type: docs
url: /de/com.aspose.slides/mathborderboxfactory/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Ermöglicht das Erstellen einer mathematischen Rahmen-Box

--------------------

Für COM-Kompatibilität
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Erstelle eine mathematische Rahmen-Box, indem sie auf das Element angewendet wird |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Erstelle eine mathematische Rahmen-Box, indem sie auf das Element angewendet wird |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


Erstelle eine mathematische Rahmen-Box, indem sie auf das Element angewendet wird

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathe-Element, dem die Rahmen-Box hinzugefügt wird |

**Rückgabewert:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - neues Border-Box-Element
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Erstelle eine mathematische Rahmen-Box, indem sie auf das Element angewendet wird

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathe-Element, dem die Rahmen-Box hinzugefügt wird |
| hideTop | boolean | Ob die obere Kante verborgen wird |
| hideBottom | boolean | Ob die untere Kante verborgen wird |
| hideLeft | boolean | Ob die linke Kante verborgen wird |
| hideRight | boolean | Ob die rechte Kante verborgen wird |
| strikethroughHorizontal | boolean | Horizontale Durchstreichung der Rahmen-Box |
| strikethroughVertical | boolean | Vertikale Durchstreichung der Rahmen-Box |
| strikethroughBottomLeftToTopRight | boolean | Diagonale Durchstreichung von unten links nach oben rechts |
| strikethroughTopLeftToBottomRight | boolean | Diagonale Durchstreichung von oben links nach unten rechts |

**Rückgabewert:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - neues Border-Box-Element