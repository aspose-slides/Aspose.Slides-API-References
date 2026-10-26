---
title: IBlurEffectiveData
second_title: Aspose.Slides für Java API Referenz
description: Unveränderliches Objekt, das einen Blur-Effekt darstellt, der auf die gesamte Form einschließlich ihrer Füllung angewendet wird.
type: docs
url: /de/com.aspose.slides/iblureffectivedata/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Unveränderliches Objekt, das einen Blur-Effekt darstellt, der auf die gesamte Form einschließlich ihrer Füllung angewendet wird. Alle Farbkanäle, einschließlich Alpha, werden beeinflusst.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRadius()](#getRadius--) | Gibt den Blurradius zurück oder setzt ihn. |
| [getGrow()](#getGrow--) | Bestimmt, ob die Begrenzungen des Objekts als Ergebnis der Unschärfe erweitert werden sollen. |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Gibt den Blurradius zurück oder setzt ihn. Read-only double.

**Rückgabe:**
double

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Bestimmt, ob die Begrenzungen des Objekts als Ergebnis der Unschärfe erweitert werden sollen. True gibt an, dass die Begrenzungen erweitert werden, während false angibt, dass dies nicht der Fall ist. Read-only boolean.

**Rückgabe:**
boolean