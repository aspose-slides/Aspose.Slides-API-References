---
title: ColorChange
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en färgändringseffekt.
type: docs
url: /sv/com.aspose.slides/colorchange/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Representerar en Color Change-effekt. Instanser av FromColor ersätts med instanser av ToColor.
## Metoder

| Method | Description |
| --- | --- |
| [getFromColor()](#getFromColor--) | Color som kommer att ersättas. |
| [getToColor()](#getToColor--) | Color som kommer att ersätta. |
| [getEffective()](#getEffective--) | Hämtar effektiva Color Change-effektsdata med arv tillämpat. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Avgör om den angivna [ColorChange](../../com.aspose.slides/colorchange) är lika med den aktuella [ColorChange](../../com.aspose.slides/colorchange). |
| [hashCode()](#hashCode--) | Fungerar som en hashfunktion för en viss typ. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

Color som kommer att ersättas. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

Color som kommer att ersätta. Skrivskyddad [IColorFormat](../../com.aspose.slides/icolorformat).

**Returnerar:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

Hämtar effektiva Color Change-effektsdata med arv tillämpat.

**Returnerar:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - En [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
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

Avgör om den angivna [ColorChange](../../com.aspose.slides/colorchange) är lika med den aktuella [ColorChange](../../com.aspose.slides/colorchange).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den [ColorChange](../../com.aspose.slides/colorchange) att jämföra. |

**Returnerar:**
boolean - true om objekten är lika; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Fungerar som en hashfunktion för en viss typ.

**Returnerar:**
int - En hashkod för det aktuella objektet.