---
title: IHtmlOptions
second_title: Aspose.Slides pro Java - referenční příručka API
description: Představuje možnosti exportu HTML.
type: docs
url: /cs/com.aspose.slides/ihtmloptions/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

Představuje možnosti exportu HTML.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | Vrací nebo nastavuje HTML šablonu. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Vrací nebo nastavuje HTML šablonu. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Vrací nebo nastavuje možnosti formátu obrázku snímku. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Vrací nebo nastavuje možnosti formátu obrázku snímku. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky, nebo ne. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky, nebo ne. |
| [getJpegQuality()](#getJpegQuality--) | Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v dokumentu PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v dokumentu PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Představuje úroveň komprese obrázků Čtení/Zápis [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Představuje úroveň komprese obrázků Čtení/Zápis [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Boolean příznak označuje, zda oříznuté části zůstávají jako součást dokumentu. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Boolean příznak označuje, zda oříznuté části zůstávají jako součást dokumentu. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True pro vyloučení atributů width a height z SVG kontejneru – to způsobí responzivní rozvržení. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True pro vyloučení atributů width a height z SVG kontejneru – to způsobí responzivní rozvržení. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Vrací nebo nastavuje hodnotu určující, zda je text vykreslen bez používání ligatur. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Vrací nebo nastavuje hodnotu určující, zda je text vykreslen bez používání ligatur. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Vrací nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Vrací nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

Vrací nebo nastavuje HTML šablonu. Čtení/Zápis [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Vrací:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

Vrací nebo nastavuje HTML šablonu. Čtení/Zápis [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

Vrací nebo nastavuje možnosti formátu obrázku snímku. Čtení/Zápis [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Vrací:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

Vrací nebo nastavuje možnosti formátu obrázku snímku. Čtení/Zápis [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Vrací:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v dokumentu PDF. Čtení/Zápis byte.

--------------------

Má efekt pouze pokud dokument obsahuje JPEG obrázky.

Použijte tuto vlastnost pro získání nebo nastavení kvality obrázků v dokumentu při ukládání do formátu PDF. Hodnota může být v rozmezí 0 až 100, kde 0 znamená nejhorší kvalitu, ale maximální kompresi, a 100 nejlepší kvalitu, ale minimální kompresi.

Výchozí hodnota je **95**.

**Vrací:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v dokumentu PDF. Čtení/Zápis byte.

--------------------

Má efekt pouze pokud dokument obsahuje JPEG obrázky.

Použijte tuto vlastnost pro získání nebo nastavení kvality obrázků v dokumentu při ukládání do formátu PDF. Hodnota může být v rozmezí 0 až 100, kde 0 znamená nejhorší kvalitu, ale maximální kompresi, a 100 nejlepší kvalitu, ale minimální kompresi.

Výchozí hodnota je **95**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Představuje úroveň komprese obrázků Čtení/Zápis [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Vrací:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Představuje úroveň komprese obrázků Čtení/Zápis [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Boolean příznak označuje, zda oříznuté části zůstávají jako součást dokumentu. Pokud je true, oříznuté části budou odstraněny, pokud je false, budou serializovány v dokumentu (což může vést k většímu souboru). Čtení/Zápis boolean.

**Vrací:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Boolean příznak označuje, zda oříznuté části zůstávají jako součást dokumentu. Pokud je true, oříznuté části budou odstraněny, pokud je false, budou serializovány v dokumentu (což může vést k většímu souboru). Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

True pro vyloučení atributů width a height z SVG kontejneru – to způsobí responzivní rozvržení. False – jinak. Čtení/Zápis boolean.

**Vrací:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

True pro vyloučení atributů width a height z SVG kontejneru – to způsobí responzivní rozvržení. False – jinak. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Vrací nebo nastavuje hodnotu určující, zda je text vykreslen bez používání ligatur. Když je nastaveno na true, ligatury budou v renderovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost false.

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

**Vrací:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Vrací nebo nastavuje hodnotu určující, zda je text vykreslen bez používání ligatur. Když je nastaveno na true, ligatury budou v renderovaném výstupu zakázány. Ve výchozím nastavení je tato vlastnost false.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Vrací nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Vrací:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Vrací nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Příklad:
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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Poskytuje možnosti, které řídí vzhled Ink objektů v exportovaném dokumentu. Pouze pro čtení [IInkOptions](../../com.aspose.slides/iinkoptions)

**Vrací:**
[IInkOptions](../../com.aspose.slides/iinkoptions)