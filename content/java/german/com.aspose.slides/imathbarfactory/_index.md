---
title: IMathBarFactory
second_title: Aspose.Slides für Java API Reference
description: Ermöglicht das Erstellen einer mathematischen Leiste
type: docs
url: /de/com.aspose.slides/imathbarfactory/
---```
public interface IMathBarFactory
```

Ermöglicht das Erstellen einer mathematischen Leiste

--------------------

Für COM-Kompatibilität
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createMathBar(IMathElement element)](#createMathBar-com.aspose.slides.IMathElement-) | Erstelle eine math bar, indem sie auf das Element angewendet wird |
| [createMathBar(IMathElement element, int position)](#createMathBar-com.aspose.slides.IMathElement-int-) | Erstelle eine math bar, indem sie auf das Element angewendet wird |
### createMathBar(IMathElement element) {#createMathBar-com.aspose.slides.IMathElement-}
```
public abstract IMathBar createMathBar(IMathElement element)
```

Erstellt eine math bar, indem sie auf das Element angewendet wird

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Matheelement, dem die Leiste hinzugefügt werden soll |

**Rückgabewert:**
[IMathBar](../../com.aspose.slides/imathbar) - neues math bar-Element
### createMathBar(IMathElement element, int position) {#createMathBar-com.aspose.slides.IMathElement-int-}
```
public abstract IMathBar createMathBar(IMathElement element, int position)
```

Erstellt eine math bar, indem sie auf das Element angewendet wird

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Matheelement, dem die Leiste hinzugefügt werden soll |
| position | int | Position der Leiste |

**Rückgabewert:**
[IMathBar](../../com.aspose.slides/imathbar) - neues math bar-Element