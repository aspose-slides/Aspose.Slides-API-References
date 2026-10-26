---
title: ISVGOptions
second_title: Aspose.Slides för Java API-referens
description: Representerar SVG-alternativ.
type: docs
url: /sv/com.aspose.slides/isvgoptions/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Representerar SVG-alternativ.
## Metoder

| Method | Beskrivning |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Bestämmer om texten på en bildruta ska sparas som grafik. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Bestämmer om texten på en bildruta ska sparas som grafik. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Returnerar eller anger den lägre upplösningsgränsen för metafilrastrering. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Returnerar eller anger den lägre upplösningsgränsen för metafilrastrering. |
| [getDisable3DText()](#getDisable3DText--) | Bestämmer om 3D-text är inaktiverad i SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Bestämmer om 3D-text är inaktiverad i SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Inaktiverar delning av FromCornerX- och FromCenter-gradienter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Inaktiverar delning av FromCornerX- och FromCenter-gradienter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 saknar möjlighet att definiera insättningar för markörer. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 saknar möjlighet att definiera insättningar för markörer. |
| [getJpegQuality()](#getJpegQuality--) | Bestämmer JPEG-kodningskvalitet. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Bestämmer JPEG-kodningskvalitet. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Returnerar och anger ett återuppringningsgränssnitt som låter användaren kontrollera formkonvertering. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Returnerar och anger ett återuppringningsgränssnitt som låter användaren kontrollera formkonvertering. |
| [getPicturesCompression()](#getPicturesCompression--) | Representerar bildkomprimeringsnivån Läs/skriv \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Representerar bildkomprimeringsnivån Läs/skriv \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | En boolesk flagga indikerar om de beskurna delarna förblir som en del av dokumentet. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | En boolesk flagga indikerar om de beskurna delarna förblir som en del av dokumentet. |
| [getUseFrameSize()](#getUseFrameSize--) | Bestämmer om textramen ska inkluderas i ett renderingsområde eller inte. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Bestämmer om textramen ska inkluderas i ett renderingsområde eller inte. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Bestämmer om den angivna rotationen av formen ska utföras vid rendering eller inte. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Bestämmer om den angivna rotationen av formen ska utföras vid rendering eller inte. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Bestämmer ett sätt att hantera externt inlästa typsnitt. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Bestämmer ett sätt att hantera externt inlästa typsnitt. |
| [getInkOptions()](#getInkOptions--) | Tillhandahåller alternativ som styr utseendet på Ink-objekt i exporterade dokument. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Hämtar eller anger ett värde som indikerar om text renderas utan att använda ligaturer. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Hämtar eller anger ett värde som indikerar om text renderas utan att använda ligaturer. |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Bestämmer om texten på en bildruta ska sparas som grafik. Läs/skriv boolean.

**Returnerar:**
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Bestämmer om texten på en bildruta ska sparas som grafik. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Returnerar eller anger den lägre upplösningsgränsen för metafilrastrering. Läs/skriv int.

**Returnerar:**
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Returnerar eller anger den lägre upplösningsgränsen för metafilrastrering. Läs/skriv int.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

Bestämmer om 3D-text är inaktiverad i SVG. Läs/skriv boolean.

**Returnerar:**
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

Bestämmer om 3D-text är inaktiverad i SVG. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

Inaktiverar delning av FromCornerX- och FromCenter-gradienter. Läs/skriv boolean.

**Returnerar:**
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

Inaktiverar delning av FromCornerX- och FromCenter-gradienter. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 saknar möjlighet att definiera insättningar för markörer. Aspose.Slides SVG-skrivmotor har en lösning för det problemet: den beskär linjeändarna med pil så att linjen inte överlappar markörer. Detta alternativ stänger av sådant beteende. Läs/skriv boolean.

**Returnerar:**
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 saknar möjlighet att definiera insättningar för markörer. Aspose.Slides SVG-skrivmotor har en lösning för det problemet: den beskär linjeändarna med pil så att linjen inte överlappar markörer. Detta alternativ stänger av sådant beteende. Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Bestämmer JPEG-kodningskvalitet. Läs/skriv int.

**Returnerar:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Bestämmer JPEG-kodningskvalitet. Läs/skriv int.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

Returnerar och anger ett återuppringningsgränssnitt som låter användaren kontrollera formkonvertering. Läs/skriv [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Returnerar:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Returnerar och anger ett återuppringningsgränssnitt som låter användaren kontrollera formkonvertering. Läs/skriv [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Representerar bildkomprimeringsnivån Läs/skriv \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Returnerar:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Representerar bildkomprimeringsnivån Läs/skriv \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

En boolesk flagga indikerar om de beskurna delarna förblir som en del av dokumentet. Om true tas de beskurna delarna bort, om false serialiseras de i dokumentet (vilket kan leda till en större fil). Läs/skriv boolean.

**Returnerar:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

En boolesk flagga indikerar om de beskurna delarna förblir som en del av dokumentet. Om true tas de beskurna delarna bort, om false serialiseras de i dokumentet (vilket kan leda till en större fil). Läs/skriv boolean.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Bestämmer om textramen ska inkluderas i ett renderingsområde eller inte. Läs/skriv boolean. Standardvärdet är false.

**Returnerar:**
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Bestämmer om textramen ska inkluderas i ett renderingsområde eller inte. Läs/skriv boolean. Standardvärdet är false.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Bestämmer om den angivna rotationen av formen ska utföras vid rendering eller inte. Läs/skriv boolean. Standardvärdet är true.

**Returnerar:**
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Bestämmer om den angivna rotationen av formen ska utföras vid rendering eller inte. Läs/skriv boolean. Standardvärdet är true.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Bestämmer ett sätt att hantera externt inlästa typsnitt. Läs/skriv [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Returnerar:**
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Bestämmer ett sätt att hantera externt inlästa typsnitt. Läs/skriv [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Tillhandahåller alternativ som styr utseendet på Ink-objekt i exporterade dokument. Skrivskyddad [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returnerar:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Hämtar eller anger ett värde som indikerar om text renderas utan att använda ligaturer. När den är satt till true, inaktiveras ligaturer i den renderade utdata. Som standard är detta egenskap satt till false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Hämtar eller anger ett värde som indikerar om text renderas utan att använda ligaturer. När den är satt till true, inaktiveras ligaturer i den renderade utdata. Som standard är detta egenskap satt till false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |