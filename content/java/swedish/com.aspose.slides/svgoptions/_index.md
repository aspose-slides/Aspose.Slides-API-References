---
title: SVGOptions
second_title: Aspose.Slides för Java API-referens
description: Representerar ett SVG-alternativ.
type: docs
url: /sv/com.aspose.slides/svgoptions/
---
**Arv:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Representerar ett SVG-alternativ.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Initierar en ny instans av klassen SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Initierar en ny instans av klassen SVGOptions och specificerar länk-embedkontrollerobjektet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Tillhandahåller alternativ som styr utseendet på Ink-objekt i exporterade dokument. |
| [getUseFrameSize()](#getUseFrameSize--) | Avgör om textramen ska inkluderas i ett renderingsområde eller inte. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Avgör om textramen ska inkluderas i ett renderingsområde eller inte. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Avgör om den angivna rotationen av formen ska utföras vid rendering eller inte. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Avgör om den angivna rotationen av formen ska utföras vid rendering eller inte. |
| [getVectorizeText()](#getVectorizeText--) | Avgör om texten på en bildspelssida ska sparas som grafik. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Avgör om texten på en bildspelssida ska sparas som grafik. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Returnerar eller ställer in den lägre upplösningsgränsen för metafilrastrering. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Returnerar eller ställer in den lägre upplösningsgränsen för metafilrastrering. |
| [getDisable3DText()](#getDisable3DText--) | Avgör om 3D-text är inaktiverad i SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Avgör om 3D-text är inaktiverad i SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Inaktiverar delning av FromCornerX- och FromCenter-gradienter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Inaktiverar delning av FromCornerX- och FromCenter-gradienter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 saknar möjlighet att definiera insets för markörer. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 saknar möjlighet att definiera insets för markörer. |
| [getDefault()](#getDefault--) | Returnerar standardinställningar. |
| [getSimple()](#getSimple--) | Returnerar inställningar för den enklaste och minsta SVG-filgenereringen. |
| [getWYSIWYG()](#getWYSIWYG--) | Returnerar inställningar för den mest exakta SVG-filgenereringen. |
| [getJpegQuality()](#getJpegQuality--) | Avgör JPEG-kodningskvalitet. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Avgör JPEG-kodningskvalitet. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Returnerar och ställer in ett återuppringningsgränssnitt som låter användaren kontrollera formkonvertering. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Returnerar och ställer in ett återuppringningsgränssnitt som låter användaren kontrollera formkonvertering. |
| [getPicturesCompression()](#getPicturesCompression--) | Representerar bildkomprimeringsnivån |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Representerar bildkomprimeringsnivån |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | En boolesk flagga indikerar om beskurna delar förblir som en del av dokumentet. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | En boolesk flagga indikerar om beskurna delar förblir som en del av dokumentet. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Avgör ett sätt att hantera externt inlästa teckensnitt. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Avgör ett sätt att hantera externt inlästa teckensnitt. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Hämtar eller anger ett värde som indikerar om text renderas utan att använda ligaturer. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Hämtar eller anger ett värde som indikerar om text renderas utan att använda ligaturer. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Initierar en ny instans av klassen SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Initierar en ny instans av klassen SVGOptions och specificerar länk-embedkontrollerobjektet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Referensen till länk-embedkontrollern. |

Link embedding controller is a delegate object that is responsible for making decisions if resources (such as images) need to be embedded or referenced as external resources.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Tillhandahåller alternativ som styr utseendet på Ink-objekt i exporterade dokument. Läs-endast [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returnerar:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Avgör om textramen ska inkluderas i ett renderingsområde eller inte. Läs/skriv  boolean . Standardvärdet är false.

**Returnerar:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Avgör om textramen ska inkluderas i ett renderingsområde eller inte. Läs/skriv  boolean . Standardvärdet är false.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Avgör om den angivna rotationen av formen ska utföras vid rendering eller inte. Läs/skriv  boolean . Standardvärdet är true.

**Returnerar:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Avgör om den angivna rotationen av formen ska utföras vid rendering eller inte. Läs/skriv  boolean . Standardvärdet är true.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Avgör om texten på en bildspelssida ska sparas som grafik. Läs/skriv boolean.

**Returnerar:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Avgör om texten på en bildspelssida ska sparas som grafik. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Returnerar eller ställer in den lägre upplösningsgränsen för metafilrastrering. Läs/skriv int.

**Returnerar:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Returnerar eller ställer in den lägre upplösningsgränsen för metafilrastrering. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Avgör om 3D-text är inaktiverad i SVG. Läs/skriv boolean.

**Returnerar:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Avgör om 3D-text är inaktiverad i SVG. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Inaktiverar delning av FromCornerX- och FromCenter-gradienter. Läs/skriv boolean.

**Returnerar:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Inaktiverar delning av FromCornerX- och FromCenter-gradienter. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 saknar möjlighet att definiera insets för markörer. Aspose.Slides SVG-skrivmotor har en lösning för detta problem: den beskär linjens slut med en pil, så att linjen inte överlappar markörerna. Detta alternativ stänger av sådant beteende. Läs/skriv boolean.

**Returnerar:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 saknar möjlighet att definiera insets för markörer. Aspose.Slides SVG-skrivmotor har en lösning för detta problem: den beskär linjens slut med en pil, så att linjen inte överlappar markörerna. Detta alternativ stänger av sådant beteende. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Returnerar standardinställningar. Läs-endast [SVGOptions](../../com.aspose.slides/svgoptions).

**Returnerar:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Returnerar inställningar för den enklaste och minsta SVG-filgenereringen. Läs-endast [SVGOptions](../../com.aspose.slides/svgoptions).

**Returnerar:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Returnerar inställningar för den mest exakta SVG-filgenereringen. Läs-endast [SVGOptions](../../com.aspose.slides/svgoptions).

**Returnerar:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Avgör JPEG-kodningskvalitet. Läs/skriv int.

**Returnerar:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Avgör JPEG-kodningskvalitet. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Returnerar och ställer in ett återuppringningsgränssnitt som låter användaren kontrollera formkonvertering. Läs/skriv [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Returnerar:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Returnerar och ställer in ett återuppringningsgränssnitt som låter användaren kontrollera formkonvertering. Läs/skriv [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Representerar bildkomprimeringsnivån

**Returnerar:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Representerar bildkomprimeringsnivån

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

En boolesk flagga indikerar om beskurna delar förblir som en del av dokumentet. Om true tas beskurna delar bort, om false kommer de att serialiseras i dokumentet (vilket kan leda till en större fil).

**Returnerar:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

En boolesk flagga indikerar om beskurna delar förblir som en del av dokumentet. Om true tas beskurna delar bort, om false kommer de att serialiseras i dokumentet (vilket kan leda till en större fil).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Avgör ett sätt att hantera externt inlästa teckensnitt. Läs/skriv [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Returnerar:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Avgör ett sätt att hantera externt inlästa teckensnitt. Läs/skriv [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Hämtar eller anger ett värde som indikerar om text renderas utan att använda ligaturer. När den är satt till true kommer ligaturer att inaktiveras i den renderade utdata. Som standard är denna egenskap satt till false.

> ```
> Exempel:
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
public final void setDisableFontLigatures(boolean value)
```

Hämtar eller anger ett värde som indikerar om text renderas utan att använda ligaturer. När den är satt till true kommer ligaturer att inaktiveras i den renderade utdata. Som standard är denna egenskap satt till false.

> ```
> Exempel:
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |