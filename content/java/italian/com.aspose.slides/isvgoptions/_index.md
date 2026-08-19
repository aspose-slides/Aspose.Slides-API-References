---
title: ISVGOptions
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta le opzioni SVG.
type: docs
url: /it/com.aspose.slides/isvgoptions/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

Rappresenta un'opzione SVG.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | Determines whether the text on a slide will be saved as graphics. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Determines whether the text on a slide will be saved as graphics. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Returns or sets the lower resolution limit for metafile rasterization. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Returns or sets the lower resolution limit for metafile rasterization. |
| [getDisable3DText()](#getDisable3DText--) | Determines whether the 3D text is disabled in SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Determines whether the 3D text is disabled in SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Disables splitting FromCornerX and FromCenter gradients. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Disables splitting FromCornerX and FromCenter gradients. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 lacks ability to define insets for markers. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 lacks ability to define insets for markers. |
| [getJpegQuality()](#getJpegQuality--) | Determines JPEG encoding quality. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Determines JPEG encoding quality. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Returns and sets a callback interface which allows user to control shape conversion. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Returns and sets a callback interface which allows user to control shape conversion. |
| [getPicturesCompression()](#getPicturesCompression--) | Represents the pictures compression level Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Represents the pictures compression level Read/write \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | A boolean flag indicates if the cropped parts remain as part of the document. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | A boolean flag indicates if the cropped parts remain as part of the document. |
| [getUseFrameSize()](#getUseFrameSize--) | Determines whether the text frame will be included in a rendering area or not. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Determines whether the text frame will be included in a rendering area or not. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Determines whether to perform the specified rotation of the shape when rendering or not. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Determines whether to perform the specified rotation of the shape when rendering or not. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Determines a way of handling externally loaded fonts. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Determines a way of handling externally loaded fonts. |
| [getInkOptions()](#getInkOptions--) | Provides options that control the look of Ink objects in exported document. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Gets or sets a value indicating whether text is rendered without using ligatures. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Gets or sets a value indicating whether text is rendered without using ligatures. |
### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Determina se il testo in una diapositiva verrà salvato come grafica. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Determina se il testo in una diapositiva verrà salvato come grafica. Lettura/Scrittura boolean.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Restituisce o imposta il limite di risoluzione inferiore per la rasterizzazione dei metafile. Lettura/Scrittura int.

**Restituisce:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Restituisce o imposta il limite di risoluzione inferiore per la rasterizzazione dei metafile. Lettura/Scrittura int.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

Determina se il testo 3D è disabilitato in SVG. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

Determina se il testo 3D è disabilitato in SVG. Lettura/Scrittura boolean.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

Disabilita la divisione dei gradienti FromCornerX e FromCenter. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

Disabilita la divisione dei gradienti FromCornerX e FromCenter. Lettura/Scrittura boolean.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 non consente di definire inset per i marker. Il motore di scrittura SVG di Aspose.Slides ha una soluzione alternativa per questo problema: taglia l’estremità della linea con la freccia, così la linea non si sovrappone ai marker. Questa opzione disattiva tale comportamento. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 non consente di definire inset per i marker. Il motore di scrittura SVG di Aspose.Slides ha una soluzione alternativa per questo problema: taglia l’estremità della linea con la freccia, così la linea non si sovrappone ai marker. Questa opzione disattiva tale comportamento. Lettura/Scrittura boolean.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Determina la qualità della codifica JPEG. Lettura/Scrittura int.

**Restituisce:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Determina la qualità della codifica JPEG. Lettura/Scrittura int.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

Restituisce e imposta un’interfaccia di callback che consente all’utente di controllare la conversione delle forme. Lettura/Scrittura [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Restituisce:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Restituisce e imposta un’interfaccia di callback che consente all’utente di controllare la conversione delle forme. Lettura/Scrittura [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Rappresenta il livello di compressione delle immagini Lettura/Scrittura \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Restituisce:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Rappresenta il livello di compressione delle immagini Lettura/Scrittura \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Un flag booleano indica se le parti ritagliate rimangono parte del documento. Se true le parti ritagliate saranno rimosse, se false saranno serializzate nel documento (ciò può portare a un file più grande). Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Un flag booleano indica se le parti ritagliate rimangono parte del documento. Se true le parti ritagliate saranno rimosse, se false saranno serializzate nel documento (ciò può portare a un file più grande). Lettura/Scrittura boolean.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Determina se il riquadro di testo sarà incluso in un’area di rendering o meno. Lettura/Scrittura boolean. Valore predefinito è false.

**Restituisce:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Determina se il riquadro di testo sarà incluso in un’area di rendering o meno. Lettura/Scrittura boolean. Valore predefinito è false.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Determina se eseguire la rotazione specificata della forma durante il rendering o no. Lettura/Scrittura boolean. Valore predefinito è true.

**Restituisce:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Determina se eseguire la rotazione specificata della forma durante il rendering o no. Lettura/Scrittura boolean. Valore predefinito è true.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Determina un modo di gestire i font caricati esternamente. Lettura/Scrittura [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Restituisce:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Determina un modo di gestire i font caricati esternamente. Lettura/Scrittura [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. Solo lettura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Restituisce:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Ottiene o imposta un valore che indica se il testo viene renderizzato senza utilizzare le legature. Quando impostato su true, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su false.

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

**Restituisce:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Ottiene o imposta un valore che indica se il testo viene renderizzato senza utilizzare le legature. Quando impostato su true, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su false.

--------------------

> ```
> Esempio:
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

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |