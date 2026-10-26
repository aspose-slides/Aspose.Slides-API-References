---
title: IHtmlOptions
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje možnosti exportu HTML.
type: docs
url: /cs/com.aspose.slides/ihtmloptions/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

Representuje možnosti exportu HTML.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | Vrací nebo nastavuje šablonu HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Vrací nebo nastavuje šablonu HTML. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Vrací nebo nastavuje možnosti formátu obrázku snímku. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Vrací nebo nastavuje možnosti formátu obrázku snímku. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky, nebo ne. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky, nebo ne. |
| [getJpegQuality()](#getJpegQuality--) | Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. |
| [getPicturesCompression()](#getPicturesCompression--) | Representuje úroveň komprese obrázků Read/write [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Representuje úroveň komprese obrázků Read/write [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Booleanový příznak udává, zda oříznuté části zůstávají součástí dokumentu. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Booleanový příznak udává, zda oříznuté části zůstávají součástí dokumentu. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True k vyloučení atributů šířky a výšky z kontejneru SVG – to zajistí responzivní rozvržení. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True k vyloučení atributů šířky a výšky z kontejneru SVG – to zajistí responzivní rozvržení. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Získává nebo nastavuje hodnotu udávající, zda je text vykreslován bez ligatur. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Získává nebo nastavuje hodnotu udávající, zda je text vykreslován bez ligatur. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Získává nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Získává nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

Vrací nebo nastavuje šablonu HTML. Read/write [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Vrací:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

Vrací nebo nastavuje šablonu HTML. Read/write [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

Vrací nebo nastavuje možnosti formátu obrázku snímku. Read/write [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Vrací:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

Vrací nebo nastavuje možnosti formátu obrázku snímku. Read/write [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

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

Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. Read/write byte.

--------------------

Má efekt pouze když dokument obsahuje JPEG obrázky.

Použijte tuto vlastnost k získání nebo nastavení kvality obrázků v dokumentu při ukládání do formátu PDF. Hodnota se může pohybovat od 0 do 100, kde 0 znamená nejhorší kvalitu, ale maximální kompresi, a 100 znamená nejlepší kvalitu, ale minimální kompresi.

Výchozí hodnota je **95**.

**Vrací:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Vrací nebo nastavuje hodnotu určující kvalitu JPEG obrázků v PDF dokumentu. Read/write byte.

--------------------

Má efekt pouze když dokument obsahuje JPEG obrázky.

Použijte tuto vlastnost k získání nebo nastavení kvality obrázků v dokumentu při ukládání do formátu PDF. Hodnota se může pohybovat od 0 do 100, kde 0 znamená nejhorší kvalitu, ale maximální kompresi, a 100 znamená nejlepší kvalitu, ale minimální kompresi.

Výchozí hodnota je **95**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Representuje úroveň komprese obrázků Read/write [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Vrací:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Representuje úroveň komprese obrázků Read/write [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Booleanový příznak udává, zda oříznuté části zůstávají součástí dokumentu. Pokud je true, oříznuté části budou odstraněny, pokud je false, budou v dokumentu serializovány (což může vést k většímu souboru) Read/write boolean.

**Vrací:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Booleanový příznak udává, zda oříznuté části zůstávají součástí dokumentu. Pokud je true, oříznuté části budou odstraněny, pokud je false, budou v dokumentu serializovány (což může vést k většímu souboru) Read/write boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

True k vyloučení atributů šířky a výšky z kontejneru SVG – to zajistí responzivní rozvržení. False – jinak. Read/write boolean.

**Vrací:**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

True k vyloučení atributů šířky a výšky z kontejneru SVG – to zajistí responzivní rozvržení. False – jinak. Read/write boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Získává nebo nastavuje hodnotu udávající, zda je text vykreslen bez použití ligatur. Když je nastaveno na true, ligatury budou ve výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na false.

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

Získává nebo nastavuje hodnotu udávající, zda je text vykreslen bez použití ligatur. Když je nastaveno na true, ligatury budou ve výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na false.

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

Získává nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

Získává nebo nastavuje režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu. Read-only [IInkOptions](../../com.aspose.slides/iinkoptions)

**Vrací:**
[IInkOptions](../../com.aspose.slides/iinkoptions)