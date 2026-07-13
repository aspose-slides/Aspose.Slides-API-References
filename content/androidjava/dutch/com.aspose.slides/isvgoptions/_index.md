---
title: ISVGOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een SVG-optie voor.
type: docs
url: /nl/com.aspose.slides/isvgoptions/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Stelt een SVG-optie voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Bepaalt of de tekst op een dia als graphics wordt opgeslagen. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Bepaalt of de tekst op een dia als graphics wordt opgeslagen. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Geeft de ondergrens van de resolutie voor metafile-rasterisatie terug of stelt deze in. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Geeft de ondergrens van de resolutie voor metafile-rasterisatie terug of stelt deze in. |
| [getDisable3DText()](#getDisable3DText--) | Bepaalt of 3D-tekst is uitgeschakeld in SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Bepaalt of 3D-tekst is uitgeschakeld in SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Schakelt het splitsen van FromCornerX- en FromCenter-verlopen uit. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Schakelt het splitsen van FromCornerX- en FromCenter-verlopen uit. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 mist de mogelijkheid om insets voor markers te definiëren. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 mist de mogelijkheid om insets voor markers te definiëren. |
| [getJpegQuality()](#getJpegQuality--) | Bepaalt de JPEG-coderingskwaliteit. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Bepaalt de JPEG-coderingskwaliteit. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Geeft een callback-interface terug en stelt deze in waarmee de gebruiker de vormconversie kan regelen. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Geeft een callback-interface terug en stelt deze in waarmee de gebruiker de vormconversie kan regelen. |
| [getPicturesCompression()](#getPicturesCompression--) | Stelt het compressieniveau van afbeeldingen voor Lezen/Schrijven #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Stelt het compressieniveau van afbeeldingen voor Lezen/Schrijven #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Een boolese vlag geeft aan of de bijgesneden delen deel blijven uitmaken van het document. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Een boolese vlag geeft aan of de bijgesneden delen deel blijven uitmaken van het document. |
| [getUseFrameSize()](#getUseFrameSize--) | Bepaalt of het tekstkader al dan niet wordt opgenomen in een weergavegebied. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Bepaalt of het tekstkader al dan niet wordt opgenomen in een weergavegebied. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Bepaalt of de opgegeven rotatie van de vorm bij het renderen wel of niet wordt uitgevoerd. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Bepaalt of de opgegeven rotatie van de vorm bij het renderen wel of niet wordt uitgevoerd. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Bepaalt hoe extern geladen lettertypen worden behandeld. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Bepaalt hoe extern geladen lettertypen worden behandeld. |
| [getInkOptions()](#getInkOptions--) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Haalt een waarde op of stelt deze in die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Bepaalt of de tekst op een dia als graphics wordt opgeslagen. Lezen/Schrijven boolese.

**Retour:**
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Bepaalt of de tekst op een dia als graphics wordt opgeslagen. Lezen/Schrijven boolese.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Geeft de ondergrens van de resolutie voor metafile-rasterisatie terug of stelt deze in. Lezen/Schrijven int.

**Retour:**
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Geeft de ondergrens van de resolutie voor metafile-rasterisatie terug of stelt deze in. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

Bepaalt of 3D-tekst is uitgeschakeld in SVG. Lezen/Schrijven boolese.

**Retour:**
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

Bepaalt of 3D-tekst is uitgeschakeld in SVG. Lezen/Schrijven boolese.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

Schakelt het splitsen van FromCornerX- en FromCenter-verlopen uit. Lezen/Schrijven boolese.

**Retour:**
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

Schakelt het splitsen van FromCornerX- en FromCenter-verlopen uit. Lezen/Schrijven boolese.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 mist de mogelijkheid om insets voor markers te definiëren. Aspose.Slides SVG-schrijfmotor heeft een oplossing voor dat probleem: hij cropt het einde van de lijn met pijl, zodat de lijn de markers niet overlapt. Deze optie schakelt dat gedrag uit. Lezen/Schrijven boolese.

**Retour:**
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 mist de mogelijkheid om insets voor markers te definiëren. Aspose.Slides SVG-schrijfmotor heeft een oplossing voor dat probleem: hij cropt het einde van de lijn met pijl, zodat de lijn de markers niet overlapt. Deze optie schakelt dat gedrag uit. Lezen/Schrijven boolese.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Bepaalt de JPEG-coderingskwaliteit. Lezen/Schrijven int.

**Retour:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Bepaalt de JPEG-coderingskwaliteit. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

Geeft een callback-interface terug en stelt deze in waarmee de gebruiker de vormconversie kan regelen. Lezen/Schrijven [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Retour:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Geeft een callback-interface terug en stelt deze in waarmee de gebruiker de vormconversie kan regelen. Lezen/Schrijven [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Stelt het compressieniveau van afbeeldingen voor Lezen/Schrijven \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Retour:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Stelt het compressieniveau van afbeeldingen voor Lezen/Schrijven \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Een boolese vlag geeft aan of de bijgesneden delen deel blijven uitmaken van het document. Indien true worden de bijgesneden delen verwijderd, indien false blijven ze geserialiseerd in het document (wat mogelijk leidt tot een groter bestand). Lezen/Schrijven boolese.

**Retour:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Een boolese vlag geeft aan of de bijgesneden delen deel blijven uitmaken van het document. Indien true worden de bijgesneden delen verwijderd, indien false blijven ze geserialiseerd in het document (wat mogelijk leidt tot een groter bestand). Lezen/Schrijven boolese.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Bepaalt of het tekstkader al dan niet wordt opgenomen in een weergavegebied. Lezen/Schrijven  boolese . Standaardwaarde is false.

**Retour:**
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Bepaalt of het tekstkader al dan niet wordt opgenomen in een weergavegebied. Lezen/Schrijven  boolese . Standaardwaarde is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Bepaalt of de opgegeven rotatie van de vorm bij het renderen wel of niet wordt uitgevoerd. Lezen/Schrijven  boolese . Standaardwaarde is true.

**Retour:**
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Bepaalt of de opgegeven rotatie van de vorm bij het renderen wel of niet wordt uitgevoerd. Lezen/Schrijven  boolese . Standaardwaarde is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Bepaalt hoe extern geladen lettertypen worden behandeld. Lezen/Schrijven [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Retour:**
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Bepaalt hoe extern geladen lettertypen worden behandeld. Lezen/Schrijven [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. Alleen-lezen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retour:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Haalt een waarde op of stelt deze in die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard staat deze eigenschap ingesteld op false.

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


**Retour:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Haalt een waarde op of stelt deze in die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard staat deze eigenschap ingesteld op false.

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


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |