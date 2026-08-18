---
title: ColorReplace
second_title: Aspose.Slides Java API Referencia
description: Egy színhelyettesítő hatást reprezentál.
type: docs
url: /hu/com.aspose.slides/colorreplace/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Minden megvalósított interfész:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Egy színhelyettesítő hatást reprezentál. Az összes effektus szín rögzített színre változik. Az alfa értékek változatlanok maradnak.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getColor()](#getColor--) | Visszatér egy színformátummal, amely minden pixel színét helyettesíti. |
| [getEffective()](#getEffective--) | Megszerezi a színhelyettesítő effektus hatékony adatait az öröklődés alkalmazásával. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Meghatározza, hogy a megadott [ColorReplace](../../com.aspose.slides/colorreplace) egyenlő-e a jelenlegi [ColorReplace](../../com.aspose.slides/colorreplace)-val. |
| [hashCode()](#hashCode--) | Hash függvényként szolgál egy adott típushoz. |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Visszatér egy színformátummal, amely minden pixel színét helyettesíti. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

Megszerezi a színhelyettesítő effektus hatékony adatait az öröklődés alkalmazásával.

**Visszatérési érték:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - Egy [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak olvasható long.

**Visszatérési érték:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Meghatározza, hogy a megadott [ColorReplace](../../com.aspose.slides/colorreplace) egyenlő-e a jelenlegi [ColorReplace](../../com.aspose.slides/colorreplace)-val.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | A [ColorReplace](../../com.aspose.slides/colorreplace) összehasonlításra. |

**Visszatérési érték:**
boolean - igaz, ha az objektumok egyenlőek; egyébként hamis.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Hash függvényként szolgál egy adott típushoz.

**Visszatérési érték:**
int - Egy hashkód a jelenlegi objektumhoz.