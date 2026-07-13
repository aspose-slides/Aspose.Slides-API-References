---
title: SVGOptions
second_title: Aspose.Slides per Android tramite il Riferimento API Java
description: Rappresenta le opzioni SVG.
type: docs
url: /it/com.aspose.slides/svgoptions/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tutte le interfacce implementate:**
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

Rappresenta le opzioni SVG.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | Inizializza una nuova istanza della classe SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | Inizializza una nuova istanza della classe SVGOptions specificando l'oggetto controller di incorporamento del collegamento. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. |
| [getUseFrameSize()](#getUseFrameSize--) | Determina se il riquadro di testo sarà incluso in un'area di rendering o meno. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | Determina se il riquadro di testo sarà incluso in un'area di rendering o meno. |
| [getUseFrameRotation()](#getUseFrameRotation--) | Determina se eseguire la rotazione specificata della forma durante il rendering o meno. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | Determina se eseguire la rotazione specificata della forma durante il rendering o meno. |
| [getVectorizeText()](#getVectorizeText--) | Determina se il testo su una diapositiva sarà salvato come grafica. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | Determina se il testo su una diapositiva sarà salvato come grafica. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | Restituisce o imposta il limite di risoluzione inferiore per la rasterizzazione dei metafile. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | Restituisce o imposta il limite di risoluzione inferiore per la rasterizzazione dei metafile. |
| [getDisable3DText()](#getDisable3DText--) | Determina se il testo 3D è disabilitato in SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | Determina se il testo 3D è disabilitato in SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | Disabilita la divisione dei gradienti FromCornerX e FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | Disabilita la divisione dei gradienti FromCornerX e FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 non dispone della capacità di definire rientri per i marcatori. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 non dispone della capacità di definire rientri per i marcatori. |
| [getDefault()](#getDefault--) | Restituisce le impostazioni predefinite. |
| [getSimple()](#getSimple--) | Restituisce le impostazioni per la generazione del file SVG più semplice e più piccolo. |
| [getWYSIWYG()](#getWYSIWYG--) | Restituisce le impostazioni per la generazione del file SVG più accurato. |
| [getJpegQuality()](#getJpegQuality--) | Determina la qualità di codifica JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Determina la qualità di codifica JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | Restituisce e imposta un'interfaccia di callback che permette all'utente di controllare la conversione delle forme. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | Restituisce e imposta un'interfaccia di callback che permette all'utente di controllare la conversione delle forme. |
| [getPicturesCompression()](#getPicturesCompression--) | Rappresenta il livello di compressione delle immagini |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Rappresenta il livello di compressione delle immagini |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Una bandiera booleana indica se le parti ritagliate rimangono come parte del documento. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Una bandiera booleana indica se le parti ritagliate rimangono come parte del documento. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | Determina il modo di gestire i caratteri caricati esternamente. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | Determina il modo di gestire i caratteri caricati esternamente. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Ottiene o imposta un valore che indica se il testo è renderizzato senza usare legature. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Ottiene o imposta un valore che indica se il testo è renderizzato senza usare legature. |
### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

Inizializza una nuova istanza della classe SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

Inizializza una nuova istanza della classe SVGOptions specificando l'oggetto controller di incorporamento del collegamento.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Il riferimento al controller di incorporamento del collegamento. |

--------------------

Il controller di incorporamento del collegamento è un oggetto delegato che è responsabile di decidere se le risorse (come le immagini) devono essere incorporate o referenziate come risorse esterne. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. Solo lettura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Restituisce:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

Determina se il riquadro di testo sarà incluso in un'area di rendering o meno. Lettura/scrittura booleano. Valore predefinito è false.

**Restituisce:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

Determina se il riquadro di testo sarà incluso in un'area di rendering o meno. Lettura/scrittura booleano. Valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

Determina se eseguire la rotazione specificata della forma durante il rendering o meno. Lettura/scrittura booleano. Valore predefinito è true.

**Restituisce:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

Determina se eseguire la rotazione specificata della forma durante il rendering o non. Lettura/scrittura booleano. Valore predefinito è true.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

Determina se il testo su una diapositiva sarà salvato come grafica. Lettura/scrittura booleano.

**Restituisce:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

Determina se il testo su una diapositiva sarà salvato come grafica. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

Restituisce o imposta il limite di risoluzione inferiore per la rasterizzazione dei metafile. Lettura/scrittura int.

**Restituisce:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

Restituisce o imposta il limite di risoluzione inferiore per la rasterizzazione dei metafile. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

Determina se il testo 3D è disabilitato in SVG. Lettura/scrittura booleano.

**Restituisce:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

Determina se il testo 3D è disabilitato in SVG. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

Disabilita la divisione dei gradienti FromCornerX e FromCenter. Lettura/scrittura booleano.

**Restituisce:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

Disabilita la divisione dei gradienti FromCornerX e FromCenter. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 non dispone della capacità di definire rientri per i marcatori. Il motore di scrittura SVG di Aspose.Slides offre una soluzione alternativa per questo problema: ritaglia l'estremità della linea con la freccia, così la linea non si sovrappone ai marcatori. Questa opzione disattiva tale comportamento. Lettura/scrittura booleano.

**Restituisce:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 non dispone della capacità di definire rientri per i marcatori. Il motore di scrittura SVG di Aspose.Slides offre una soluzione alternativa per questo problema: ritaglia l'estremità della linea con la freccia, così la linea non si sovrappone ai marcatori. Questa opzione disattiva tale comportamento. Lettura/scrittura booleano.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

Restituisce le impostazioni predefinite. Solo lettura [SVGOptions](../../com.aspose.slides/svgoptions).

**Restituisce:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

Restituisce le impostazioni per la generazione del file SVG più semplice e più piccolo. Solo lettura [SVGOptions](../../com.aspose.slides/svgoptions).

**Restituisce:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

Restituisce le impostazioni per la generazione del file SVG più accurato. Solo lettura [SVGOptions](../../com.aspose.slides/svgoptions).

**Restituisce:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Determina la qualità di codifica JPEG. Lettura/scrittura int.

**Restituisce:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Determina la qualità di codifica JPEG. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

Restituisce e imposta un'interfaccia di callback che permette all'utente di controllare la conversione delle forme. Lettura/scrittura [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Restituisce:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

Restituisce e imposta un'interfaccia di callback che permette all'utente di controllare la conversione delle forme. Lettura/scrittura [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Rappresenta il livello di compressione delle immagini

**Restituisce:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Rappresenta il livello di compressione delle immagini

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Una bandiera booleana indica se le parti ritagliate rimangono come parte del documento. Se true le parti ritagliate saranno rimosse, se false saranno serializzate nel documento (il che può portare a un file più grande)

**Restituisce:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Una bandiera booleana indica se le parti ritagliate rimangono come parte del documento. Se true le parti ritagliate saranno rimosse, se false saranno serializzate nel documento (il che può portare a un file più grande)

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

Determina il modo di gestire i caratteri caricati esternamente. Lettura/scrittura [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Restituisce:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

Determina il modo di gestire i caratteri caricati esternamente. Lettura/scrittura [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Ottiene o imposta un valore che indica se il testo è renderizzato senza usare legature. Quando impostato su true, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su false.

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
public final void setDisableFontLigatures(boolean value)
```

Ottiene o imposta un valore che indica se il testo è renderizzato senza usare legature. Quando impostato su true, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su false.

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |