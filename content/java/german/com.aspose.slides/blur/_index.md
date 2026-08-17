---
title: Blur
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Blur-Effekt dar, der auf die gesamte Form einschließlich ihrer Füllung angewendet wird.
type: docs
url: /de/com.aspose.slides/blur/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Stellt einen Blur-Effekt dar, der auf die gesamte Form, einschließlich ihrer Füllung, angewendet wird. Alle Farbkanäle, einschließlich Alpha, sind betroffen.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getRadius()](#getRadius--) | Gibt den Blur-Radius zurück oder legt ihn fest. |
| [setRadius(double value)](#setRadius-double-) | Gibt den Blur-Radius zurück oder legt ihn fest. |
| [getGrow()](#getGrow--) | Bestimmt, ob die Grenzen des Objekts als Ergebnis des Unschärfeeffekts vergrößert werden sollen. |
| [setGrow(boolean value)](#setGrow-boolean-) | Bestimmt, ob die Grenzen des Objekts als Ergebnis des Unschärfeeffekts vergrößert werden sollen. |
| [getEffective()](#getEffective--) | Ruft die wirksamen Blur-Effektdaten mit angewandter Vererbung ab. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestimmt, ob das angegebene [Blur](../../com.aspose.slides/blur) dem aktuellen [Blur](../../com.aspose.slides/blur) entspricht. |
| [hashCode()](#hashCode--) | Dient als Hash-Funktion für einen bestimmten Typ. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Gibt den Blur-Radius zurück oder legt ihn fest. Lesen/Schreiben double.

**Rückgabe:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Gibt den Blur-Radius zurück oder legt ihn fest. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

Bestimmt, ob die Grenzen des Objekts als Ergebnis des Unschärfeeffekts vergrößert werden sollen. Wahr bedeutet, dass die Grenzen vergrößert werden, während falsch bedeutet, dass dies nicht der Fall ist. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

Bestimmt, ob die Grenzen des Objekts als Ergebnis des Unschärfeeffekts vergrößert werden sollen. Wahr bedeutet, dass die Grenzen vergrößert werden, während falsch bedeutet, dass dies nicht der Fall ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

Ruft die wirksamen Blur-Effektdaten mit angewandter Vererbung ab.

**Rückgabe:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - Ein [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Bestimmt, ob das angegebene [Blur](../../com.aspose.slides/blur) dem aktuellen [Blur](../../com.aspose.slides/blur) entspricht.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Der [Blur](../../com.aspose.slides/blur) zum Vergleich. |

**Rückgabe:**
boolean - true, wenn Objekte gleich sind; andernfalls false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Dient als Hash-Funktion für einen bestimmten Typ.

**Rückgabe:**
int - Ein Hash-Code für das aktuelle Objekt.