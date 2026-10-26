---
title: IBlurEffectiveData
second_title: Aspose.Slides für Android über Java API-Referenz
description: Unveränderliches Objekt, das einen Blur-Effekt darstellt, der auf die gesamte Form einschließlich ihrer Füllung angewendet wird.
type: docs
url: /de/com.aspose.slides/iblureffectivedata/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Unveränderliches Objekt, das einen Blur-Effekt darstellt, der auf die gesamte Form einschließlich ihrer Füllung angewendet wird. Alle Farbkanäle, einschließlich Alpha, sind betroffen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRadius()](#getRadius--) | Gibt den Blur-Radius zurück oder setzt ihn. |
| [getGrow()](#getGrow--) | Bestimmt, ob die Begrenzungen des Objekts infolge der Unschärfe vergrößert werden sollen. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Gibt den Blur-Radius zurück oder setzt ihn. Nur-Lese double.

**Rückgabe:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Bestimmt, ob die Begrenzungen des Objekts infolge der Unschärfe vergrößert werden sollen. True zeigt an, dass die Begrenzungen vergrößert werden, während false anzeigt, dass dies nicht der Fall ist. Nur-Lese boolean.

**Rückgabe:**
boolean