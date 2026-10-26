---
title: SVGOptions
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een SVG-optie.
type: docs
url: /nl/com.aspose.slides/svgoptions/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Stelt een SVG-optie voor.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Initialiseert een nieuw exemplaar van de SVGOptions-klasse. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Initialiseert een nieuw exemplaar van de SVGOptions-klasse met specificatie van het link-embed-controllerobject. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. |
| [getUseFrameSize()](#getUseFrameSize--) | Bepaalt of het tekstkader wel of niet wordt opgenomen in een rendergebied. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Bepaalt of het tekstkader wel of niet wordt opgenomen in een rendergebied. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Bepaalt of de opgegeven rotatie van de vorm tijdens het renderen moet worden uitgevoerd. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Bepaalt of de opgegeven rotatie van de vorm tijdens het renderen moet worden uitgevoerd. |
| [getVectorizeText()](#getVectorizeText--) | Bepaalt of de tekst op een dia als grafisch wordt opgeslagen. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Bepaalt of de tekst op een dia als grafisch wordt opgeslagen. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Retourneert of stelt de ondergrens voor resolutie bij metafile-rasterisatie in. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Retourneert of stelt de ondergrens voor resolutie bij metafile-rasterisatie in. |
| [getDisable3DText()](#getDisable3DText--) | Bepaalt of 3D-tekst in SVG is uitgeschakeld. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Bepaalt of 3D-tekst in SVG is uitgeschakeld. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Schakelt het splitsen van FromCornerX- en FromCenter-kleurverlopen uit. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Schakelt het splitsen van FromCornerX- en FromCenter-kleurverlopen uit. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 ontbreekt de mogelijkheid om insetten voor markeringen te definiëren. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 ontbreekt de mogelijkheid om insetten voor markeringen te definiëren. |
| [getDefault()](#getDefault--) | Retourneert de standaardinstellingen. |
| [getSimple()](#getSimple--) | Retourneert instellingen voor de eenvoudigste en kleinste SVG-bestandsgeneratie. |
| [getWYSIWYG()](#getWYSIWYG--) | Retourneert instellingen voor de meest nauwkeurige SVG-bestandsgeneratie. |
| [getJpegQuality()](#getJpegQuality--) | Bepaalt de JPEG-coderingskwaliteit. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Bepaalt de JPEG-coderingskwaliteit. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Retourneert en stelt een callback-interface in waarmee de gebruiker de vormconversie kan beheren. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Retourneert en stelt een callback-interface in waarmee de gebruiker de vormconversie kan beheren. |
| [getPicturesCompression()](#getPicturesCompression--) | Vertegenwoordigt het compressieniveau van de afbeeldingen |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Vertegenwoordigt het compressieniveau van de afbeeldingen |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Een booleaanse vlag die aangeeft of de bijgesneden delen als onderdeel van het document blijven. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Een booleaanse vlag die aangeeft of de bijgesneden delen als onderdeel van het document blijven. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Bepaalt de manier waarop extern geladen lettertypen worden afgehandeld. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Bepaalt de manier waarop extern geladen lettertypen worden afgehandeld. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Haalt of stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Haalt of stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Initialiseert een nieuw exemplaar van de SVGOptions-klasse.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Initialiseert een nieuw exemplaar van de SVGOptions-klasse met specificatie van het link-embed-controllerobject.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | De referentie naar de link-embed-controller. |

--------------------

Link-embed-controller is een delegate-object dat verantwoordelijk is voor het nemen van beslissingen of bronnen (zoals afbeeldingen) moeten worden ingesloten of als externe bronnen worden verwezen. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Biedt opties die het uiterlijk van Ink-objecten in het geëxporteerde document regelen. Alleen-lezen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Returns:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Bepaalt of het tekstkader wel of niet wordt opgenomen in een rendergebied. Lezen/Schrijven boolean. Standaardwaarde is false.

**Returns:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Bepaalt of het tekstkader wel of niet wordt opgenomen in een rendergebied. Lezen/Schrijven boolean. Standaardwaarde is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Bepaalt of de opgegeven rotatie van de vorm tijdens het renderen moet worden uitgevoerd. Lezen/Schrijven boolean. Standaardwaarde is true.

**Returns:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Bepaalt of de opgegeven rotatie van de vorm tijdens het renderen moet worden uitgevoerd. Lezen/Schrijven boolean. Standaardwaarde is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Bepaalt of de tekst op een dia als grafisch wordt opgeslagen. Lezen/Schrijven boolean.

**Returns:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Bepaalt of de tekst op een dia als grafisch wordt opgeslagen. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Retourneert of stelt de ondergrens voor resolutie bij metafile-rasterisatie in. Lezen/Schrijven int.

**Returns:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Retourneert of stelt de ondergrens voor resolutie bij metafile-rasterisatie in. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Bepaalt of 3D-tekst in SVG is uitgeschakeld. Lezen/Schrijven boolean.

**Returns:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Bepaalt of 3D-tekst in SVG is uitgeschakeld. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Schakelt het splitsen van FromCornerX- en FromCenter-kleurverlopen uit. Lezen/Schrijven boolean.

**Returns:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Schakelt het splitsen van FromCornerX- en FromCenter-kleurverlopen uit. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 ontbreekt de mogelijkheid om insetten voor markeringen te definiëren. Aspose.Slides SVG-schrijfmotor heeft een oplossing voor dat probleem: het bijsnijdt het einde van een lijn met een pijl, zodat de lijn de markeringen niet overlapt. Deze optie schakelt dergelijk gedrag uit. Lezen/Schrijven boolean.

**Returns:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 ontbreekt de mogelijkheid om insetten voor markeringen te definiëren. Aspose.Slides SVG-schrijfmotor heeft een oplossing voor dat probleem: het bijsnijdt het einde van een lijn met een pijl, zodat de lijn de markeringen niet overlapt. Deze optie schakelt dergelijk gedrag uit. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Retourneert de standaardinstellingen. Alleen-lezen [SVGOptions](../../com.aspose.slides/svgoptions).

**Returns:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Retourneert instellingen voor de eenvoudigste en kleinste SVG-bestandsgeneratie. Alleen-lezen [SVGOptions](../../com.aspose.slides/svgoptions).

**Returns:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Retourneert instellingen voor de meest nauwkeurige SVG-bestandsgeneratie. Alleen-lezen [SVGOptions](../../com.aspose.slides/svgoptions).

**Returns:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Bepaalt de JPEG-coderingskwaliteit. Lezen/Schrijven int.

**Returns:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Bepaalt de JPEG-coderingskwaliteit. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Retourneert en stelt een callback-interface in waarmee de gebruiker de vormconversie kan beheren. Lezen/Schrijven [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Returns:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Retourneert en stelt een callback-interface in waarmee de gebruiker de vormconversie kan beheren. Lezen/Schrijven [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Vertegenwoordigt het compressieniveau van de afbeeldingen

**Returns:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Vertegenwoordigt het compressieniveau van de afbeeldingen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Een booleaanse vlag die aangeeft of de bijgesneden delen als onderdeel van het document blijven. Als true worden de bijgesneden delen verwijderd, als false worden ze geserialiseerd in het document (wat mogelijk leidt tot een groter bestand)

**Returns:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Een booleaanse vlag die aangeeft of de bijgesneden delen als onderdeel van het document blijven. Als true worden de bijgesneden delen verwijderd, als false worden ze geserialiseerd in het document (wat mogelijk leidt tot een groter bestand)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Bepaalt de manier waarop extern geladen lettertypen worden afgehandeld. Lezen/Schrijven [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Returns:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Bepaalt de manier waarop extern geladen lettertypen worden afgehandeld. Lezen/Schrijven [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Haalt of stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de gerenderde output. Standaard is deze eigenschap false.

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

**Returns:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Haalt of stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de gerenderde output. Standaard is deze eigenschap false.

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