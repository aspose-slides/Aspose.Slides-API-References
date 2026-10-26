---
title: Blur
second_title: Aspose.Slides Android számára Java API hivatkozás
description: Egy Blur effektust képvisel, amely az egész alakzatra, beleértve a kitöltését is, alkalmazva van.
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

Egy Blur effektust képvisel, amely az egész alakzatra, beleértve a kitöltését is, alkalmazva van. Minden színcsatorna, beleértve az alfát is, érintett.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getRadius()](#getRadius--) | Visszaadja vagy beállítja a blur sugarát. |
| [setRadius(double value)](#setRadius-double-) | Visszaadja vagy beállítja a blur sugarát. |
| [getGrow()](#getGrow--) | Meghatározza, hogy az objektum határai a elmosódás következtében növekedjenek-e. |
| [setGrow(boolean value)](#setGrow-boolean-) | Meghatározza, hogy az objektum határai a elmosódás következtében növekedjenek-e. |
| [getEffective()](#getEffective--) | A öröklődés alkalmazásával kapott hatékony Blur effektus adatot adja vissza. |
| [equals(Object obj)](#equals-java.lang.Object-) | Meghatározza, hogy a megadott [Blur](../../com.aspose.slides/blur) egyenlő-e a jelenlegi [Blur](../../com.aspose.slides/blur)-val. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Visszaadja vagy beállítja a blur sugarát. Olvasás/írás double.

**Visszatér:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Visszaadja vagy beállítja a blur sugarát. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```


Meghatározza, hogy az objektum határai a elmosódás következtében növekedjenek-e. True jelzi, hogy a határok növekednek, false pedig, hogy nem. Olvasás/írás boolean.

**Visszatér:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```


Meghatározza, hogy az objektum határai a elmosódás következtében növekedjenek-e. True jelzi, hogy a határok növekednek, false pedig, hogy nem. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```


A öröklődés alkalmazásával kapott hatékony Blur effektus adatot adja vissza.

**Visszatér:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - A [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Meghatározza, hogy a megadott [Blur](../../com.aspose.slides/blur) egyenlő-e a jelenlegi [Blur](../../com.aspose.slides/blur)-val.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | Az [Blur](../../com.aspose.slides/blur) az összehasonlításhoz. |

**Visszatér:**
boolean - true, ha az objektumok egyenlőek; egyébként false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash függvényként szolgál egy adott típushoz.

**Visszatér:**
int - Egy hash kód az aktuális objektumhoz.