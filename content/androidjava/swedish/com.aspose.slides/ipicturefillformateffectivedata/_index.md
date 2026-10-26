---
title: IPictureFillFormatEffectiveData
second_title: Aspose.Slides för Android via Java API-referens
description: Oföränderligt objekt som innehåller egenskaperna för bildfyllning.
type: docs
url: /sv/com.aspose.slides/ipicturefillformateffectivedata/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IPictureFillFormatEffectiveData extends IFillParamSource
```

Oföränderligt objekt som innehåller egenskaperna för bildfyllning.

--------------------

Detta gränssnitt används som en del av [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDpi()](#getDpi--) | Returnerar dpi som används för att fylla en bild. |
| [getPictureFillMode()](#getPictureFillMode--) | Returnerar bildfyllningsläget. |
| [getPicture()](#getPicture--) | Returnerar bilden. |
| [getCropLeft()](#getCropLeft--) | Returnerar antalet procent av den verkliga bildbredden som beskärs bort från bildens vänstra sida. |
| [getCropTop()](#getCropTop--) | Returnerar antalet procent av den verkliga bildhöjden som beskärs bort från bildens övre sida. |
| [getCropRight()](#getCropRight--) | Returnerar antalet procent av den verkliga bildbredden som beskärs bort från bildens högra sida. |
| [getCropBottom()](#getCropBottom--) | Returnerar antalet procent av den verkliga bildhöjden som beskärs bort från bildens nedre sida. |
### getDpi() {#getDpi--}
```
public abstract int getDpi()
```

Returnerar dpi som används för att fylla en bild. Skrivskyddad int.

**Returnerar:**
int
### getPictureFillMode() {#getPictureFillMode--}
```
public abstract int getPictureFillMode()
```

Returnerar bildfyllningsläget. Skrivskyddad [PictureFillMode](../../com.aspose.slides/picturefillmode).

**Returnerar:**
int
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

Returnerar bilden. Skrivskyddad [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata).

**Returnerar:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getCropLeft() {#getCropLeft--}
```
public abstract float getCropLeft()
```

Returnerar antalet procent av den verkliga bildbredden som beskärs bort från bildens vänstra sida. Skrivskyddad float.

**Returnerar:**
float
### getCropTop() {#getCropTop--}
```
public abstract float getCropTop()
```

Returnerar antalet procent av den verkliga bildhöjden som beskärs bort från bildens övre sida. Skrivskyddad float.

**Returnerar:**
float
### getCropRight() {#getCropRight--}
```
public abstract float getCropRight()
```

Returnerar antalet procent av den verkliga bildbredden som beskärs bort från bildens högra sida. Skrivskyddad float.

**Returnerar:**
float
### getCropBottom() {#getCropBottom--}
```
public abstract float getCropBottom()
```

Returnerar antalet procent av den verkliga bildhöjden som beskärs bort från bildens nedre sida. Skrivskyddad float.

**Returnerar:**
float