---
title: IMathBarFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Ermöglicht das Erstellen einer Math-Leiste
type: docs
url: /de/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

Ermöglicht das Erstellen einer Math-Leiste

--------------------

Für COM-Kompatibilität
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Erstelle eine Math-Leiste, indem sie auf das Element angewendet wird |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Erstelle eine Math-Leiste, indem sie auf das Element angewendet wird |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```

Erstelle eine Math-Leiste, indem sie auf das Element angewendet wird

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathe-Element, dem die Leiste hinzugefügt werden soll |

**Rückgabewert:**
[IMathBar](../../com.aspose.slides/imathbar) - neues Math-Leisten-Element
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```

Erstelle eine Math-Leiste, indem sie auf das Element angewendet wird

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Mathe-Element, dem die Leiste hinzugefügt werden soll |
| position | int | Position der Leiste |

**Rückgabewert:**
[IMathBar](../../com.aspose.slides/imathbar) - neues Math-Leisten-Element