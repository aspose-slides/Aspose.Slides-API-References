---
title: HtmlOptions
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta le opzioni di esportazione HTML.
type: docs
url: /it/com.aspose.slides/htmloptions/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tutte le interfacce implementate:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

Rappresenta le opzioni di esportazione HTML.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Crea un nuovo oggetto HtmlOptions specificando il callback. |
| [HtmlOptions()](#HtmlOptions--) | Crea un nuovo oggetto HtmlOptions per salvare in un singolo file HTML. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifica se il documento generato deve includere o meno le diapositive nascoste. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifica se il documento generato deve includere o meno le diapositive nascoste. |
| [getHtmlFormatter()](#getHtmlFormatter--) | Ottiene o imposta il modello HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Ottiene o imposta il modello HTML. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Ottiene o imposta un valore che indica se il testo viene visualizzato senza utilizzare le legature. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Ottiene o imposta un valore che indica se il testo viene visualizzato senza utilizzare le legature. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Ottiene o imposta le opzioni di formato immagine della diapositiva. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Ottiene o imposta le opzioni di formato immagine della diapositiva. |
| [getJpegQuality()](#getJpegQuality--) | Ottiene o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Ottiene o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Rappresenta il livello di compressione delle immagini |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Rappresenta il livello di compressione delle immagini |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Un flag booleano indica se le parti ritagliate rimangono come parte del documento. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Un flag booleano indica se le parti ritagliate rimangono come parte del documento. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True per escludere gli attributi width e height dal contenitore svg - questo renderà il layout responsivo. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True per escludere gli attributi width e height dal contenitore svg - questo renderà il layout responsivo. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```


Crea un nuovo oggetto HtmlOptions specificando il callback.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Oggetto callback che controlla il salvataggio del progetto. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```


Crea un nuovo oggetto HtmlOptions per salvare in un singolo file HTML.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Restituisce:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Ottiene o imposta la modalità in cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


Fornisce opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. Solo lettura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Restituisce:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Specifica se il documento generato deve includere o meno le diapositive nascoste. Il valore predefinito è false.

**Restituisce:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Specifica se il documento generato deve includere o meno le diapositive nascoste. Il valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```


Ottiene o imposta il modello HTML. Lettura/Scrittura [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Restituisce:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```


Ottiene o imposta il modello HTML. Lettura/Scrittura [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


Ottiene o imposta un valore che indica se il testo viene visualizzato senza utilizzare le legature. Quando impostato su true, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
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


Ottiene o imposta un valore che indica se il testo viene visualizzato senza utilizzare le legature. Quando impostato su true, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata su false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```


Ottiene o imposta le opzioni di formato immagine della diapositiva. Lettura/Scrittura [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Restituisce:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```


Ottiene o imposta le opzioni di formato immagine della diapositiva. Lettura/Scrittura [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```


Ottiene o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF. Lettura/Scrittura byte.

Ha effetto solo quando un documento contiene immagini JPEG.

Utilizza questa proprietà per ottenere o impostare la qualità delle immagini all'interno di un documento quando si salva in formato PDF. Il valore può variare da 0 a 100 dove 0 indica la qualità peggiore ma la massima compressione e 100 indica la migliore qualità ma la minima compressione.

Il valore predefinito è **95**.

**Restituisce:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```


Ottiene o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF. Lettura/Scrittura byte.

Ha effetto solo quando un documento contiene immagini JPEG.

Utilizza questa proprietà per ottenere o impostare la qualità delle immagini all'interno di un documento quando si salva in formato PDF. Il valore può variare da 0 a 100 dove 0 indica la qualità peggiore ma la massima compressione e 100 indica la migliore qualità ma la minima compressione.

Il valore predefinito è **95**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

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


Un flag booleano indica se le parti ritagliate rimangono come parte del documento. Se true le parti ritagliate saranno rimosse, se false saranno serializzate nel documento (il che può portare a un file più grande)

**Restituisce:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```


Un flag booleano indica se le parti ritagliate rimangono come parte del documento. Se true le parti ritagliate saranno rimosse, se false saranno serializzate nel documento (il che può portare a un file più grande)

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```


True per escludere gli attributi width e height dal contenitore svg - questo renderà il layout responsivo. False - altrimenti. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```


True per escludere gli attributi width e height dal contenitore svg - questo renderà il layout responsivo. False - altrimenti. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |