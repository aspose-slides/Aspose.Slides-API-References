---
title: HSL
second_title: Aspose.Slides Java API Referencia
description: Hue/Saturation/Luminance hatást reprezentál.
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

Egy Hue/Saturation/Luminance hatást reprezentál. Az árnyalat, a telítettség és a fényerő mindegyike a jelenlegi értékéhez viszonyítva állítható.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getEffective()](#getEffective--) | Lekéri a hatékony Hue/Saturation/Luminance effektus adatokat az öröklés alkalmazásával. |
| [equals(Object obj)](#equals-java.lang.Object-) | Megállapítja, hogy a megadott [HSL](../../com.aspose.slides/hsl) egyenlő-e a jelenlegi [HSL](../../com.aspose.slides/hsl)-val. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |

### getEffective() {#getEffective--}
```
public final IHSLEffectiveData getEffective()
```

Lekéri a hatékony Hue/Saturation/Luminance effektus adatokat az öröklés alkalmazásával.

**Visszatérési érték:**
[IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata) - A [IHSLEffectiveData](../../com.aspose.slides/ihsleffectivedata).

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
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz.

**Visszatérési érték:**
int - Egy hash kód a jelenlegi objektumhoz.