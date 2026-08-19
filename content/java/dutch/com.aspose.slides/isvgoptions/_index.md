---
title: ISVGOptions
second_title: Aspose.Slides voor Java API-referentie
description: Stelt de SVG-opties voor.
type: docs
url: /nl/com.aspose.slides/isvgoptions/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Stelt de SVG-opties voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Bepaalt of de tekst op een dia wordt opgeslagen als grafische afbeelding. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Bepaalt of de tekst op een dia wordt opgeslagen als grafische afbeelding. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Retourneert of stelt de ondergrens van de resolutie voor metafile-rasterisatie in. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Retourneert of stelt de ondergrens van de resolutie voor metafile-rasterisatie in. |
| [getDisable3DText()](#getDisable3DText--) | Bepaalt of 3D-tekst is uitgeschakeld in SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Bepaalt of 3D-tekst is uitgeschakeld in SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Schakelt het splitsen van FromCornerX- en FromCenter-gradienten uit. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Schakelt het splitsen van FromCornerX- en FromCenter-gradienten uit. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 mist de mogelijkheid om inspringingen voor markers te definiëren. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 mist de mogelijkheid om inspringingen voor markers te definiëren. |
| [getJpegQuality()](#getJpegQuality--) | Bepaalt de JPEG-coderingskwaliteit. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Bepaalt de JPEG-coderingskwaliteit. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Retourneert en stelt een callback-interface in die de gebruiker in staat stelt de vormconversie te beheren. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Retourneert en stelt een callback-interface in die de gebruiker in staat stelt de vormconversie te beheren. |
| [getPicturesCompression()](#getPicturesCompression--) | Stelt het compressieniveau van afbeeldingen voor Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Stelt het compressieniveau van afbeeldingen voor Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Een boolean-vlag geeft aan of de bijgesneden delen onderdeel blijven van het document. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Een boolean-vlag geeft aan of de bijgesneden delen onderdeel blijven van het document. |
| [getUseFrameSize()](#getUseFrameSize--) | Bepaalt of het tekstkader al dan niet wordt opgenomen in een rendergebied. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Bepaalt of het tekstkader al dan niet wordt opgenomen in een rendergebied. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Bepaalt of de opgegeven rotatie van de vorm bij het renderen moet worden uitgevoerd of niet. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Bepaalt of de opgegeven rotatie van de vorm bij het renderen moet worden uitgevoerd of niet. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Bepaalt hoe extern geladen lettertypen worden afgehandeld. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Bepaalt hoe extern geladen lettertypen worden afgehandeld. |
| [getInkOptions()](#getInkOptions--) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Haalt een waarde op of stelt deze in die aangeeft of tekst wordt gerenderd zonder ligaturen. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Haalt een waarde op of stelt deze in die aangeeft of tekst wordt gerenderd zonder ligaturen. |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Bepaalt of de tekst op een dia wordt opgeslagen als grafische afbeelding. Lezen/Schrijven boolean.

**Retour:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Bepaalt of de tekst op een dia wordt opgeslagen als grafische afbeelding. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Retourneert of stelt de ondergrens van de resolutie voor metafile-rasterisatie in. Lezen/Schrijven int.

**Retour:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Retourneert of stelt de ondergrens van de resolutie voor metafile-rasterisatie in. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

Bepaalt of 3D-tekst is uitgeschakeld in SVG. Lezen/Schrijven boolean.

**Retour:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

Bepaalt of 3D-tekst is uitgeschakeld in SVG. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

Schakelt het splitsen van FromCornerX- en FromCenter-gradienten uit. Lezen/Schrijven boolean.

**Retour:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

Schakelt het splitsen van FromCornerX- en FromCenter-gradienten uit. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 mist de mogelijkheid om inspringingen voor markers te definiëren. De SVG-schrijfmotor van Aspose.Slides heeft een oplossing voor dat probleem: hij knipt het einde van de lijn met een pijl af, zodat de lijn de markers niet overlapt. Deze optie schakelt dergelijk gedrag uit. Lezen/Schrijven boolean.

**Retour:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 mist de mogelijkheid om inspringingen voor markers te definiëren. De SVG-schrijfmotor van Aspose.Slides heeft een oplossing voor dat probleem: hij knipt het einde van de lijn met een pijl af, zodat de lijn de markers niet overlapt. Deze optie schakelt dergelijk gedrag uit. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

Retourneert en stelt een callback-interface in die de gebruiker in staat stelt de vormconversie te beheren. Lezen/Schrijven [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Retour:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Retourneert en stelt een callback-interface in die de gebruiker in staat stelt de vormconversie te beheren. Lezen/Schrijven [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parameters:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Een boolean-vlag geeft aan of de bijgesneden delen onderdeel blijven van het document. Indien true worden de bijgesneden delen verwijderd, indien false worden ze geserialiseerd in het document (wat kan leiden tot een groter bestand). Lezen/Schrijven boolean.

**Retour:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Een boolean-vlag geeft aan of de bijgesneden delen onderdeel blijven van het document. Indien true worden de bijgesneden delen verwijderd, indien false worden ze geserialiseerd in het document (wat kan leiden tot een groter bestand). Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Bepaalt of het tekstkader al dan niet wordt opgenomen in een rendergebied. Lezen/Schrijven boolean. Standaardwaarde is false.

**Retour:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Bepaalt of het tekstkader al dan niet wordt opgenomen in een rendergebied. Lezen/Schrijven boolean. Standaardwaarde is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Bepaalt of de opgegeven rotatie van de vorm bij het renderen moet worden uitgevoerd of niet. Lezen/Schrijven boolean. Standaardwaarde is true.

**Retour:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Bepaalt of de opgegeven rotatie van de vorm bij het renderen moet worden uitgevoerd of niet. Lezen/Schrijven boolean. Standaardwaarde is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Bepaalt hoe extern geladen lettertypen worden afgehandeld. Lezen/Schrijven [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Retour:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Bepaalt hoe extern geladen lettertypen worden afgehandeld. Lezen/Schrijven [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parameters:**
| Parameter | Type | Description |
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

Haalt een waarde op of stelt deze in die aangeeft of tekst wordt gerenderd zonder ligaturen. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de uitgevoerde output. Standaard is deze eigenschap false.

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

Haalt een waarde op of stelt deze in die aangeeft of tekst wordt gerenderd zonder ligaturen. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de uitgevoerde output. Standaard is deze eigenschap false.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |