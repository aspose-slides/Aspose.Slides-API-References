---
title: ColorReplace
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en färgbyteseffekt.
type: docs
url: /sv/com.aspose.slides/colorreplace/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Representerar en färgbyteseffekt. Alla effektfärger ändras till en fast färg. Alfa-värden påverkas inte.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColor()](#getColor--) | Returnerar färgformat som kommer att ersätta färgen på varje pixel. |
| [getEffective()](#getEffective--) | Hämtar effektiv färgbyteseffektsdata med arv applicerat. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om den angivna [ColorReplace](../../com.aspose.slides/colorreplace) är lika med den aktuella [ColorReplace](../../com.aspose.slides/colorreplace). |
| [hashCode()](#hashCode--) | Fungera som en hash-funktion för en viss typ. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Returnerar färgformat som kommer att ersätta färgen på varje pixel. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```


Hämtar effektiv färgbyteseffektsdata med arv applicerat.

**Returnerar:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - En [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Skrivskyddad long.

**Returnerar:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om den angivna [ColorReplace](../../com.aspose.slides/colorreplace) är lika med den aktuella [ColorReplace](../../com.aspose.slides/colorreplace).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det [ColorReplace](../../com.aspose.slides/colorreplace) att jämföra. |

**Returnerar:**
boolean - true om objekten är lika; annars, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Fungerar som en hash-funktion för en viss typ.

**Returnerar:**
int - En hash-kod för det aktuella objektet.