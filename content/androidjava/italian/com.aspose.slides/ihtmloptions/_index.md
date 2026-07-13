---
title: IHtmlOptions
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta le opzioni di esportazione HTML.
type: docs
url: /it/com.aspose.slides/ihtmloptions/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

Rappresenta le opzioni di esportazione HTML.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | Restituisce o imposta il modello HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Restituisce o imposta il modello HTML. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Restituisce o imposta le opzioni del formato immagine della diapositiva. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Restituisce o imposta le opzioni del formato immagine della diapositiva. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Specifica se il documento generato deve includere le diapositive nascoste o meno. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Specifica se il documento generato deve includere le diapositive nascoste o meno. |
| [getJpegQuality()](#getJpegQuality--) | Restituisce o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Restituisce o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Rappresenta il livello di compressione delle immagini Lettura/Scrittura [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Rappresenta il livello di compressione delle immagini Lettura/Scrittura [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Un flag booleano indica se le parti ritagliate rimangono parte del documento. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Un flag booleano indica se le parti ritagliate rimangono parte del documento. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True per escludere gli attributi width e height dal contenitore SVG - ciò renderà il layout responsivo. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True per escludere gli attributi width e height dal contenitore SVG - ciò renderà il layout responsivo. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Ottiene o imposta un valore che indica se il testo è renderizzato senza utilizzare le legature. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Ottiene o imposta un valore che indica se il testo è renderizzato senza utilizzare le legature. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Ottiene o imposta la modalità con cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Ottiene o imposta la modalità con cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Fornisce le opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. |
### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```


Restituisce o imposta il modello HTML. Lettura/Scrittura [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Restituisce:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```


Restituisce o imposta il modello HTML. Lettura/Scrittura [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```


Restituisce o imposta le opzioni del formato immagine della diapositiva. Lettura/Scrittura [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Restituisce:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```


Restituisce o imposta le opzioni del formato immagine della diapositiva. Lettura/Scrittura [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Specifică se il documento generato deve includere le diapositive nascoste o meno. Il valore predefinito è false.

**Restituisce:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Specifică se il documento generato deve includere le diapositive nascoste o meno. Il valore predefinito è false.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```


Restituisce o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF. Lettura/Scrittura byte.

--------------------

Ha effetto solo quando un documento contiene immagini JPEG.

Utilizzare questa proprietà per ottenere o impostare la qualità delle immagini all'interno di un documento durante il salvataggio in formato PDF. Il valore può variare da 0 a 100, dove 0 indica la peggiore qualità ma massima compressione e 100 indica la migliore qualità ma minima compressione.

Il valore predefinito è **95**.

**Restituisce:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```


Restituisce o imposta un valore che determina la qualità delle immagini JPEG all'interno del documento PDF. Lettura/Scrittura byte.

--------------------

Ha effetto solo quando un documento contiene immagini JPEG.

Utilizzare questa proprietà per ottenere o impostare la qualità delle immagini all'interno di un documento durante il salvataggio in formato PDF. Il valore può variare da 0 a 100, dove 0 indica la peggiore qualità ma massima compressione e 100 indica la migliore qualità ma minima compressione.

Il valore predefinito è **95**.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```


Rappresenta il livello di compressione delle immagini Lettura/Scrittura [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Restituisce:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```


Rappresenta il livello di compressione delle immagini Lettura/Scrittura [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```


Un flag booleano indica se le parti ritagliate rimangono parte del documento. Se true le parti ritagliate saranno rimosse, se false saranno serializzate nel documento (il che può portare a un file più grande) Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```


Un flag booleano indica se le parti ritagliate rimangono parte del documento. Se true le parti ritagliate saranno rimosse, se false saranno serializzate nel documento (il che può portare a un file più grande) Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```


True per escludere gli attributi width e height dal contenitore SVG - ciò renderà il layout responsivo. False - altrimenti. Lettura/Scrittura boolean.

**Restituisce:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```


True per escludere gli attributi width e height dal contenitore SVG - ciò renderà il layout responsivo. False - altrimenti. Lettura/Scrittura boolean.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```


Ottiene o imposta un valore che indica se il testo è renderizzato senza utilizzare le legature. Quando impostato a true, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata a false.

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
public abstract void setDisableFontLigatures(boolean value)
```


Ottiene o imposta un valore che indica se il testo è renderizzato senza utilizzare le legature. Quando impostato a true, le legature saranno disabilitate nell'output renderizzato. Per impostazione predefinita, questa proprietà è impostata a false.

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

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```


Ottiene o imposta la modalità con cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Esempio:
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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Ottiene o imposta la modalità con cui le diapositive sono posizionate sulla pagina durante l'esportazione di una presentazione [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Esempio:
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
public abstract IInkOptions getInkOptions()
```


Fornisce le opzioni che controllano l'aspetto degli oggetti Ink nel documento esportato. Sola lettura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Restituisce:**
[IInkOptions](../../com.aspose.slides/iinkoptions)