---
title: ISVGOptions
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta un'opzione SVG.
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
| [getVectorizeText()](#getVectorizeText--) | Determina se il testo su una diapositiva verrà salvato come grafica. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Determina se il testo su una diapositiva verrà salvato come grafica. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Restituisce o imposta il limite di risoluzione inferiore per la rasterizzazione dei metafile. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Restituisce o imposta il limite di risoluzione inferiore per la rasterizzazione dei metafile. |
| [getDisable3DText()](#getDisable3DText--) | Determina se il testo 3D è disabilitato in SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Determina se il testo 3D è disabilitato in SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Disabilita la divisione dei gradienti FromCornerX e FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Disabilita la divisione dei gradienti FromCornerX e FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 non consente di definire gli spazi interni per i marcatori. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 non consente di definire gli spazi interni per i marcatori. |
| [getJpegQuality()](#getJpegQuality--) | Determina la qualità della codifica JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Determina la qualità della codifica JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Restituisce e imposta un'interfaccia di callback che permette all'utente di controllare la conversione della forma. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Restituisce e imposta un'interfaccia di callback che permette all'utente di controllare la conversione della forma. |
| [getPicturesCompression()](#getPicturesCompression--) | Rappresenta il livello di compressione delle immagini Lettura/scrittura #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Rappresenta il livello di compressione delle immagini Lettura/scrittura #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Un flag booleano indica se le parti ritagliate rimangono parte del documento. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Un flag booleano indica se le parti ritagliate rimangono parte del documento. |
| [getUseFrameSize()](#getUseFrameSize--) | Determina se il riquadro di testo sarà incluso in un'area di rendering o meno. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Determina se il riquadro di testo sarà incluso in un'area di rendering o meno. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Determina se eseguire la rotazione specificata della forma durante il rendering o meno. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Determina se eseguire la rotazione specificata della forma durante il rendering o meno. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Determina il modo di gestire i font caricati esternamente. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Determina il modo di gestire i font caricati esternamente. |
| [getInkOptions()](#getInkOptions--) | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Ottiene o imposta un valore che indica se il testo è renderizzato senza utilizzare le legature. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Ottiene o imposta un valore che indica se il testo è renderizzato senza utilizzare le legature. |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

Determina se il testo su una diapositiva verrà salvato come grafica. Lettura/scrittura booleano.

**Restituisce:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

Determina se il testo su una diapositiva verrà salvato come grafica. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

Restituisce o imposta il limite di risoluzione inferiore per la rasterizzazione dei metafile. Lettura/scrittura int.

**Restituisce:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

Restituisce o imposta il limite di risoluzione inferiore per la rasterizzazione dei metafile. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

Determina se il testo 3D è disabilitato in SVG. Lettura/scrittura booleano.

**Restituisce:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

Determina se il testo 3D è disabilitato in SVG. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

Disabilita la divisione dei gradienti FromCornerX e FromCenter. Lettura/scrittura booleano.

**Restituisce:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

Disabilita la divisione dei gradienti FromCornerX e FromCenter. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

SVG 1.1 non consente di definire gli spazi interni per i marcatori. Il motore di scrittura SVG di Aspose.Slides ha una soluzione alternativa per questo problema: ritaglia l'estremità della linea con la freccia, così la linea non si sovrappone ai marcatori. Questa opzione disattiva tale comportamento. Lettura/scrittura booleano.

**Restituisce:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

SVG 1.1 non consente di definire gli spazi interni per i marcatori. Il motore di scrittura SVG di Aspose.Slides ha una soluzione alternativa per questo problema: ritaglia l'estremità della linea con la freccia, così la linea non si sovrappone ai marcatori. Questa opzione disattiva tale comportamento. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

Determina la qualità della codifica JPEG. Lettura/scrittura int.

**Restituisce:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

Determina la qualità della codifica JPEG. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

Restituisce e imposta un'interfaccia di callback che permette all'utente di controllare la conversione della forma. Lettura/scrittura [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Restituisce:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

Restituisce e imposta un'interfaccia di callback che permette all'utente di controllare la conversione della forma. Lettura/scrittura [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Rappresenta il livello di compressione delle immagini Lettura/scrittura #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int).

**Restituisce:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Rappresenta il livello di compressione delle immagini Lettura/scrittura #getPicturesCompression.getPicturesCompression/#setPicturesCompression(int).setPicturesCompression(int).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Un flag booleano indica se le parti ritagliate rimangono parte del documento. Se true le parti ritagliate saranno rimosse, se false saranno serializzate nel documento (il che può portare a un file più grande) Lettura/scrittura booleano.

**Restituisce:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Un flag booleano indica se le parti ritagliate rimangono parte del documento. Se true le parti ritagliate saranno rimosse, se false saranno serializzate nel documento (il che può portare a un file più grande) Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

Determina se il riquadro di testo sarà incluso in un'area di rendering o meno. Lettura/scrittura booleano. Il valore predefinito è false.

**Restituisce:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

Determina se il riquadro di testo sarà incluso in un'area di rendering o meno. Lettura/scrittura booleano. Il valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

Determina se eseguire la rotazione specificata della forma durante il rendering o meno. Lettura/scrittura booleano. Il valore predefinito è true.

**Restituisce:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

Determina se eseguire la rotazione specificata della forma durante il rendering o meno. Lettura/scrittura booleano. Il valore predefinito è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

Determina il modo di gestire i font caricati esternamente. Lettura/scrittura [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Restituisce:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

Determina il modo di gestire i font caricati esternamente. Lettura/scrittura [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. Sola lettura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Restituisce:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Ottiene o imposta un valore che indica se il testo è renderizzato senza utilizzare le legature. Quando impostato su true, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su false.

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

Ottiene o imposta un valore che indica se il testo è renderizzato senza utilizzare le legature. Quando impostato su true, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su false.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |