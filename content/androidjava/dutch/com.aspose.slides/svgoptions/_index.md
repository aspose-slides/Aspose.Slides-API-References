---
title: SVGOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een SVG-optie voor.
type: docs
url: /nl/com.aspose.slides/svgoptions/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle Geïmplementeerde Interfaces:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Stelt een SVG-optie voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Initialiseert een nieuw exemplaar van de SVGOptions-klasse. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Initialiseert een nieuw exemplaar van de SVGOptions-klasse waarbij het link-embedcontrollerobject wordt gespecificeerd. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. |
| [getUseFrameSize()](#getUseFrameSize--) | Bepaalt of het tekstkader wel of niet wordt opgenomen in een rendergebied. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Bepaalt of het tekstkader wel of niet wordt opgenomen in een rendergebied. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Bepaalt of de opgegeven rotatie van de vorm wel of niet wordt uitgevoerd bij het renderen. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Bepaalt of de opgegeven rotatie van de vorm wel of niet wordt uitgevoerd bij het renderen. |
| [getVectorizeText()](#getVectorizeText--) | Bepaalt of de tekst op een dia wordt opgeslagen als grafische afbeelding. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Bepaalt of de tekst op een dia wordt opgeslagen als grafische afbeelding. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Retourneert of stelt de ondergrens voor resolutie bij rasterisatie van metafiles in. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Retourneert of stelt de ondergrens voor resolutie bij rasterisatie van metafiles in. |
| [getDisable3DText()](#getDisable3DText--) | Bepaalt of 3D-tekst is uitgeschakeld in SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Bepaalt of 3D-tekst is uitgeschakeld in SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Schakelt het splitsen van FromCornerX- en FromCenter-gradaties uit. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Schakelt het splitsen van FromCornerX- en FromCenter-gradaties uit. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 mist de mogelijkheid om inspringingen voor markers te definiëren. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 mist de mogelijkheid om inspringingen voor markers te definiëren. |
| [getDefault()](#getDefault--) | Retourneert standaardinstellingen. |
| [getSimple()](#getSimple--) | Retourneert instellingen voor de eenvoudigste en kleinste SVG-bestandsgeneratie. |
| [getWYSIWYG()](#getWYSIWYG--) | Retourneert instellingen voor de meest nauwkeurige SVG-bestandsgeneratie. |
| [getJpegQuality()](#getJpegQuality--) | Bepaalt de kwaliteit van JPEG-codering. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Bepaalt de kwaliteit van JPEG-codering. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Retourneert en stelt een callback-interface in die de gebruiker in staat stelt de vormconversie te controleren. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Retourneert en stelt een callback-interface in die de gebruiker in staat stelt de vormconversie te controleren. |
| [getPicturesCompression()](#getPicturesCompression--) | Stelt het compressieniveau van afbeeldingen voor |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Stelt het compressieniveau van afbeeldingen voor |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Een booleaanse vlag geeft aan of de bijgesneden delen behouden blijven als onderdeel van het document. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Een booleaanse vlag geeft aan of de bijgesneden delen behouden blijven als onderdeel van het document. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Bepaalt een manier om extern geladen lettertypen te verwerken. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Bepaalt een manier om extern geladen lettertypen te verwerken. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Haalt op of stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Haalt op of stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen. |

### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Initialiseert een nieuw exemplaar van de SVGOptions-klasse.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Initialiseert een nieuw exemplaar van de SVGOptions-klasse waarbij het link-embedcontrollerobject wordt gespecificeerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | De link-embedcontroller-referentie. |

--------------------

De link-embedcontroller is een delegatieobject dat verantwoordelijk is voor het nemen van beslissingen of bronnen (zoals afbeeldingen) moeten worden ingeembed of als externe bronnen moeten worden verwezen. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. Alleen-lezen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Retour:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Bepaalt of het tekstkader wel of niet wordt opgenomen in een rendergebied. Lezen/Schrijven boolean . Standaardwaarde is false.

**Retour:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Bepaalt of het tekstkader wel of niet wordt opgenomen in een rendergebied. Lezen/Schrijven boolean . Standaardwaarde is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Bepaalt of de opgegeven rotatie van de vorm wel of niet wordt uitgevoerd bij het renderen. Lezen/Schrijven boolean . Standaardwaarde is true.

**Retour:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Bepaalt of de opgegeven rotatie van de vorm wel of niet wordt uitgevoerd bij het renderen. Lezen/Schrijven boolean . Standaardwaarde is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Bepaalt of de tekst op een dia wordt opgeslagen als grafische afbeelding. Lezen/Schrijven boolean.

**Retour:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Bepaalt of de tekst op een dia wordt opgeslagen als grafische afbeelding. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Retourneert of stelt de ondergrens voor resolutie bij rasterisatie van metafiles in. Lezen/Schrijven int.

**Retour:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Retourneert of stelt de ondergrens voor resolutie bij rasterisatie van metafiles in. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Bepaalt of 3D-tekst is uitgeschakeld in SVG. Lezen/Schrijven boolean.

**Retour:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Bepaalt of 3D-tekst is uitgeschakeld in SVG. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Schakelt het splitsen van FromCornerX- en FromCenter-gradaties uit. Lezen/Schrijven boolean.

**Retour:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Schakelt het splitsen van FromCornerX- en FromCenter-gradaties uit. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 mist de mogelijkheid om inspringingen voor markers te definiëren. Aspose.Slides SVG-schrijfmotor heeft een oplossing voor dat probleem: hij snijdt het einde van een lijn met een pijl af, zodat de lijn de markers niet overlapt. Deze optie schakelt dat gedrag uit. Lezen/Schrijven boolean.

**Retour:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 mist de mogelijkheid om inspringingen voor markers te definiëren. Aspose.Slides SVG-schrijfmotor heeft een oplossing voor dat probleem: hij snijdt het einde van een lijn met een pijl af, zodat de lijn de markers niet overlapt. Deze optie schakelt dat gedrag uit. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Retourneert standaardinstellingen. Alleen-lezen [SVGOptions](../../com.aspose.slides/svgoptions).

**Retour:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Retourneert instellingen voor de eenvoudigste en kleinste SVG-bestandsgeneratie. Alleen-lezen [SVGOptions](../../com.aspose.slides/svgoptions).

**Retour:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Retourneert instellingen voor de meest nauwkeurige SVG-bestandsgeneratie. Alleen-lezen [SVGOptions](../../com.aspose.slides/svgoptions).

**Retour:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Bepaalt de kwaliteit van JPEG-codering. Lezen/Schrijven int.

**Retour:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Bepaalt de kwaliteit van JPEG-codering. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Retourneert en stelt een callback-interface in die de gebruiker in staat stelt de vormconversie te controleren. Lezen/Schrijven [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Retour:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Retourneert en stelt een callback-interface in die de gebruiker in staat stelt de vormconversie te controleren. Lezen/Schrijven [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Stelt het compressieniveau van afbeeldingen voor

**Retour:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Stelt het compressieniveau van afbeeldingen voor

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Een booleaanse vlag geeft aan of de bijgesneden delen behouden blijven als onderdeel van het document. Indien true worden de bijgesneden delen verwijderd, bij false worden ze geserialiseerd in het document (wat kan leiden tot een groter bestand)

**Retour:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Een booleaanse vlag geeft aan of de bijgesneden delen behouden blijven als onderdeel van het document. Indien true worden de bijgesneden delen verwijderd, bij false worden ze geserialiseerd in het document (wat kan leiden tot een groter bestand)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Bepaalt een manier om extern geladen lettertypen te verwerken. Lezen/Schrijven [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Retour:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Bepaalt een manier om extern geladen lettertypen te verwerken. Lezen/Schrijven [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Haalt op of stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard is deze eigenschap false.

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
public final void setDisableFontLigatures(boolean value)
```

Haalt op of stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard is deze eigenschap false.

--------------------

> ```
> Voorbeeld:
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