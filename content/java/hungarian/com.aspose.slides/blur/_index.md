---
title: Blur
second_title: Aspose.Slides Java API referencia
description: Egy Blur effektust képvisel, amely az egész alakzatra, beleértve a kitöltést, kerül alkalmazásra.
type: docs
url: /hu/com.aspose.slides/blur/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden megvalósított interfész:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Egy Blur effektust képvisel, amely az egész alakzatra, beleértve a kitöltést is, alkalmazásra kerül. Minden színcsatorna, beleértve az alfát is, érintett.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getRadius()](#getRadius--) | Visszaadja vagy beállítja a blur radius-ot. |
| [setRadius(double value)](#setRadius-double-) | Visszaadja vagy beállítja a blur radius-ot. |
| [getGrow()](#getGrow--) | Megállapítja, hogy az objektum határai növekedni kell-e a elmosódás következtében. |
| [setGrow(boolean value)](#setGrow-boolean-) | Megállapítja, hogy az objektum határai növekedni kell-e a elmosódás következtében. |
| [getEffective()](#getEffective--) | Lekéri a hatékony Blur effektusadatokat az öröklődés alkalmazásával. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [Blur](../../com.aspose.slides/blur) egyenlő-e a jelenlegi [Blur](../../com.aspose.slides/blur). |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típusra. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Visszaadja vagy beállítja a blur radius-t. Olvasás/írás double.

**Visszatér:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Visszaadja vagy beállítja a blur radius-t. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

Megállapítja, hogy az objektum határai növekedni kell-e a elmosódás következtében. True jelzi, hogy a határok növekednek, míg false jelzi, hogy nem. Olvasás/írás boolean.

**Visszatér:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

Megállapítja, hogy az objektum határai növekedni kell-e a elmosódás következtében. True jelzi, hogy a határok növekednek, míg false jelzi, hogy nem. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

Lekéri a hatékony Blur effektusadatokat az öröklődés alkalmazásával.

**Visszatér:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - A [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Megállapítja, hogy a megadott [Blur](../../com.aspose.slides/blur) egyenlő-e a jelenlegi [Blur](../../com.aspose.slides/blur).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [Blur](../../com.aspose.slides/blur) összehasonlításához. |

**Visszatér:**
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típusra.

**Visszatér:**
int - Egy hash kód a jelenlegi objektumhoz.