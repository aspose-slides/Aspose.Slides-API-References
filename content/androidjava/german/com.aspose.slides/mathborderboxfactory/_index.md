---
title: MathBorderBoxFactory
second_title: Aspose.Slides für Android über Java API Referenz
description: Ermöglicht das Erstellen einer mathematischen Randbox
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

Ermöglicht das Erstellen einer mathematischen Randbox

--------------------

Für COM-Kompatibilität
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Erstellt eine mathematische Randbox, indem sie auf das Element angewendet wird |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Erstellt eine mathematische Randbox, indem sie auf das Element angewendet wird |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```

### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```

Erstellt eine mathematische Randbox, indem sie auf das Element angewendet wird

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathe-Element, dem die Randbox hinzugefügt wird |

**Rückgabewert:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - neues Randbox-Element
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Erstellt eine mathematische Randbox, indem sie auf das Element angewendet wird

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathe-Element, dem die Randbox hinzugefügt wird |
| hideTop | boolean | Obere Kante ausblenden |
| hideBottom | boolean | Untere Kante ausblenden |
| hideLeft | boolean | Linke Kante ausblenden |
| hideRight | boolean | Rechte Kante ausblenden |
| strikethroughHorizontal | boolean | Horizontale Durchstreichung der Randbox |
| strikethroughVertical | boolean | Vertikale Durchstreichung der Randbox |
| strikethroughBottomLeftToTopRight | boolean | Durchstreichung der Randbox von unten links nach oben rechts |
| strikethroughTopLeftToBottomRight | boolean | Durchstreichung der Randbox von oben links nach unten rechts |

**Rückgabewert:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - neues Randbox-Element