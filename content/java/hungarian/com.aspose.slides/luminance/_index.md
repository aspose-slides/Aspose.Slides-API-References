---
title: Luminance
second_title: Aspose.Slides Java API referencia
description: Luminancia hatást képvisel.
type: docs
url: /hu/com.aspose.slides/luminance/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden megvalósított interfész:**
[com.aspose.slides.ILuminance](../../com.aspose.slides/iluminance), com.aspose.slides.IVisualEffect
```
public final class Luminance extends ImageTransformOperation implements ILuminance, IVisualEffect
```

Luminancia hatást képviseli. A fényerő lineárisan közelebb hozza az összes színt a fehérhez vagy a feketéhez. A kontraszt minden színt úgy méretez, hogy azok közelebb vagy távolabb kerüljenek egymástól.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getEffective()](#getEffective--) | Az öröklődéssel alkalmazott hatékony Luminancia effektus adatokat adja vissza. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [Luminance](../../com.aspose.slides/luminance) megegyezik-e a jelenlegi [Luminance](../../com.aspose.slides/luminance)-val. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getEffective() {#getEffective--}
```
public final ILuminanceEffectiveData getEffective()
```


Az öröklődéssel alkalmazott hatékony Luminancia effektus adatokat adja vissza.

**Visszatérési érték:**
[ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata) - A [ILuminanceEffectiveData](../../com.aspose.slides/iluminanceeffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Megállapítja, hogy a megadott [Luminance](../../com.aspose.slides/luminance) megegyezik-e a jelenlegi [Luminance](../../com.aspose.slides/luminance)-val.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [Luminance](../../com.aspose.slides/luminance) összehasonlításra. |

**Visszatérési érték:**
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash függvényként szolgál egy adott típushoz.

**Visszatérési érték:**
int - A jelenlegi objektum hash kódja.