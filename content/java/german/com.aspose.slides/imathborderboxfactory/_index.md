---
title: IMathBorderBoxFactory
second_title: Aspose.Slides für Java API-Referenz
description: Ermöglicht das Erstellen eines mathematischen Randkastens
type: docs
url: /de/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Ermöglicht das Erstellen eines mathematischen Randkastens

--------------------

Für COM-Kompatibilität
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Create a math border box by applying to the element |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Create a math border box by applying to the element |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Erstellt einen mathematischen Randkasten, indem er auf das Element angewendet wird

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | mathematisches Element, dem der Randkasten angewendet wird |

**Rückgabewert:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - neues Randkasten-Element
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Erstellt einen mathematischen Randkasten, indem er auf das Element angewendet wird

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | mathematisches Element, dem der Randkasten angewendet wird |
| hideTop | boolean | Obere Kante ausblenden |
| hideBottom | boolean | Untere Kante ausblenden |
| hideLeft | boolean | Linke Kante ausblenden |
| hideRight | boolean | Rechte Kante ausblenden |
| strikethroughHorizontal | boolean | Horizontale Durchstreichung des Randkastens |
| strikethroughVertical | boolean | Vertikale Durchstreichung des Randkastens |
| strikethroughBottomLeftToTopRight | boolean | Durchstreichung des Randkastens von unten links nach oben rechts |
| strikethroughTopLeftToBottomRight | boolean | Durchstreichung des Randkastens von oben links nach unten rechts |

**Rückgabewert:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - neues Randkasten-Element