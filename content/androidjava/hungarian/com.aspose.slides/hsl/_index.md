---
title: HSL
second_title: Aspose.Slides for Android a Java API-referenciája szerint
description: Hue/Saturation/Luminance effektust ábrázol.
type: docs
url: /hu/com.aspose.slides/hsl/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden megvalósított interfész:**
[com.aspose.slides.IHSL](../../com.aspose.slides/ihsl), com.aspose.slides.IVisualEffect
```
public final class HSL extends ImageTransformOperation implements IHSL, IVisualEffect
```

Egy Hue/Saturation/Luminance effektust ábrázol. A hue, saturation és luminance minden egyes értéke módosítható az aktuális értékéhez képest.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getEffective()](#getEffective--) | Lekéri a hatékony Hue/Saturation/Luminance effektusadatokat az öröklődés alkalmazásával. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [HSL](../../com.aspose.slides/hsl) egyenlő-e a jelenlegi [HSL](../../com.aspose.slides/hsl)-vel. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |
### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```

Lekéri a hatékony Hue/Saturation/Luminance effektusadatokat az öröklődés alkalmazásával.

**Visszatérési érték:**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - Egy [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Megállapítja, hogy a megadott [HSL](../../com.aspose.slides/hsl) egyenlő-e a jelenlegi [HSL](../../com.aspose.slides/hsl)-vel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [HSL](../../com.aspose.slides/hsl) a összehasonlításhoz. |

**Visszatérési érték:**
boolean - true ha az objektumok egyenlőek; egyébként false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz.

**Visszatérési érték:**
int - Az aktuális objektum hashkódja.