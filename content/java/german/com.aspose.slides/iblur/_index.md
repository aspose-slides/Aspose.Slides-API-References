---
title: IBlur
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Blur-Effekt dar, der auf die gesamte Form einschließlich ihrer Füllung angewendet wird.
type: docs
url: /de/com.aspose.slides/iblur/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Stellt einen Blur-Effekt dar, der auf die gesamte Form, einschließlich ihrer Füllung, angewendet wird. Alle Farbkanäle, einschließlich Alpha, sind betroffen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRadius()](#getRadius--) | Gibt zurück oder setzt den Unschärferadius. |
| [setRadius(double value)](#setRadius-double-) | Gibt zurück oder setzt den Unschärferadius. |
| [getGrow()](#getGrow--) | Bestimmt, ob die Grenzen des Objekts als Ergebnis der Unschärfe vergrößert werden sollen. |
| [setGrow(boolean value)](#setGrow-boolean-) | Bestimmt, ob die Grenzen des Objekts als Ergebnis der Unschärfe vergrößert werden sollen. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Gibt zurück oder setzt den Unschärferadius. Lesen/Schreiben double.

**Rückgabe:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Gibt zurück oder setzt den Unschärferadius. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Bestimmt, ob die Grenzen des Objekts als Ergebnis der Unschärfe vergrößert werden sollen. True gibt an, dass die Grenzen vergrößert werden, während false angibt, dass dies nicht der Fall ist. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Bestimmt, ob die Grenzen des Objekts als Ergebnis der Unschärfe vergrößert werden sollen. True gibt an, dass die Grenzen vergrößert werden, während false angibt, dass dies nicht der Fall ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |