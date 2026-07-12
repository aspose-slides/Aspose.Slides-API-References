---
title: IBlur
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Unschärfeeffekt dar, der auf die gesamte Form einschließlich ihrer Füllung angewendet wird.
type: docs
url: /de/com.aspose.slides/iblur/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

Stellt einen Unschärfeeffekt dar, der auf die gesamte Form, einschließlich ihrer Füllung, angewendet wird. Alle Farbkanäle, einschließlich Alpha, werden beeinflusst.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRadius()](#getRadius--) | Gibt den Unschärferadius zurück oder setzt ihn. |
| [setRadius(double value)](#setRadius-double-) | Gibt den Unschärferadius zurück oder setzt ihn. |
| [getGrow()](#getGrow--) | Bestimmt, ob die Begrenzungen des Objekts durch das Unschärfen vergrößert werden sollen. True bedeutet, dass die Begrenzungen vergrößert werden, während false bedeutet, dass sie nicht vergrößert werden. |
| [setGrow(boolean value)](#setGrow-boolean-) | Bestimmt, ob die Begrenzungen des Objekts durch das Unschärfen vergrößert werden sollen. True bedeutet, dass die Begrenzungen vergrößert werden, während false bedeutet, dass sie nicht vergrößert werden. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Gibt den Unschärferadius zurück oder setzt ihn. Lese/Schreib double.

**Rückgabewert:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

Gibt den Unschärferadius zurück oder setzt ihn. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Bestimmt, ob die Begrenzungen des Objekts durch das Unschärfen vergrößert werden sollen. True bedeutet, dass die Begrenzungen vergrößert werden, während false bedeutet, dass sie nicht vergrößert werden. Lese/Schreib boolean.

**Rückgabewert:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

Bestimmt, ob die Begrenzungen des Objekts durch das Unschärfen vergrößert werden sollen. True bedeutet, dass die Begrenzungen vergrößert werden, während false bedeutet, dass sie nicht vergrößert werden. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |