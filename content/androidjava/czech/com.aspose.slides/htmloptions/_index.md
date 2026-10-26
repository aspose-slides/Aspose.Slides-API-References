---
title: HtmlOptions
second_title: Aspose.Slides pro Android – reference Java API
description: Reprezentuje možnosti exportu do HTML.
type: docs
url: /cs/com.aspose.slides/htmloptions/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Všechny implementované rozhraní:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

Reprezentuje možnosti exportu do HTML.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Vytvoří nový objekt HtmlOptions specifikující zpětné volání. |
| [HtmlOptions()](#HtmlOptions--) | Vytvoří nový objekt HtmlOptions pro ukládání do jediného souboru HTML. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky, nebo ne. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky, nebo ne. |
| [getHtmlFormatter()](#getHtmlFormatter--) | Vrací nebo nastaví šablonu HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Vrací nebo nastaví šablonu HTML. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Získá nebo nastaví hodnotu určující, zda je text vykreslen bez použití ligatur. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Získá nebo nastaví hodnotu určující, zda je text vykreslen bez použití ligatur. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Vrací nebo nastaví možnosti formátu obrázku snímku. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Vrací nebo nastaví možnosti formátu obrázku snímku. |
| [getJpegQuality()](#getJpegQuality--) | Vrací nebo nastaví hodnotu určující kvalitu JPEG obrázků uvnitř PDF dokumentu. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Vrací nebo nastaví hodnotu určující kvalitu JPEG obrázků uvnitř PDF dokumentu. |
| [getPicturesCompression()](#getPicturesCompression--) | Reprezentuje úroveň komprese obrázků |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Reprezentuje úroveň komprese obrázků |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Boolean příznak, který udává, zda oříznuté části zůstávají součástí dokumentu. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Boolean příznak, který udává, zda oříznuté části zůstávají součástí dokumentu. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True pro vyloučení atributů šířky a výšky ze svg kontejneru – to učiní rozvržení responzivním. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True pro vyloučení atributů šířky a výšky ze svg kontejneru – to učiní rozvržení responzivním. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

Vytvoří nový objekt HtmlOptions specifikující zpětné volání.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Objekt zpětného volání, který řídí ukládání projektu. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

Vytvoří nový objekt HtmlOptions pro ukládání do jediného souboru HTML.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Získá nebo nastaví režim, ve kterém jsou snímky umístěny na stránce při exportu prezentace [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final IInkOptions getInkOptions()
```

Poskytuje možnosti, které řídí vzhled objektů Ink v exportovaném dokumentu. Pouze ke čtení [IInkOptions](../../com.aspose.slides/iinkoptions)

**Vrací:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Vrací:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Určuje, zda vygenerovaný dokument má zahrnovat skryté snímky, nebo ne. Výchozí hodnota je false.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

Vrací nebo nastaví šablonu HTML. Čtení/Zápis [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Vrací:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

Vrací nebo nastaví šablonu HTML. Čtení/Zápis [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Získá nebo nastaví hodnotu určující, zda je text vykreslen bez použití ligatur. Když je nastavena na true, ligatury budou ve výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na false.

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
public final void setDisableFontLigatures(boolean value)
```

Získá nebo nastaví hodnotu určující, zda je text vykreslen bez použití ligatur. Když je nastavena na true, ligatury budou ve výstupu zakázány. Ve výchozím nastavení je tato vlastnost nastavena na false.

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

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

Vrací nebo nastaví možnosti formátu obrázku snímku. Čtení/Zápis [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Vrací:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

Vrací nebo nastaví možnosti formátu obrázku snímku. Čtení/Zápis [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Vrací nebo nastaví hodnotu určující kvalitu JPEG obrázků uvnitř PDF dokumentu. Čtení/Zápis byte.

--------------------

Má efekt pouze když dokument obsahuje JPEG obrázky.

Použijte tuto vlastnost k získání nebo nastavení kvality obrázků uvnitř dokumentu při ukládání ve formátu PDF. Hodnota se může pohybovat od 0 do 100, kde 0 znamená nejhorší kvalitu, ale maximální kompresi, a 100 znamená nejlepší kvalitu, ale minimální kompresi.

Výchozí hodnota je **95**.

**Vrací:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Vrací nebo nastaví hodnotu určující kvalitu JPEG obrázků uvnitř PDF dokumentu. Čtení/Zápis byte.

--------------------

Má efekt pouze když dokument obsahuje JPEG obrázky.

Použijte tuto vlastnost k získání nebo nastavení kvality obrázků uvnitř dokumentu při ukládání ve formátu PDF. Hodnota se může pohybovat od 0 do 100, kde 0 znamená nejhorší kvalitu, ale maximální kompresi, a 100 znamená nejlepší kvalitu, ale minimální kompresi.

Výchozí hodnota je **95**.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Reprezentuje úroveň komprese obrázků

**Vrací:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Reprezentuje úroveň komprese obrázků

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Boolean příznak, který udává, zda oříznuté části zůstávají součástí dokumentu. Pokud je true, oříznuté části budou odstraněny, pokud je false, budou v dokumentu serializovány (což může vést k většímu souboru)

**Vrací:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Boolean příznak, který udává, zda oříznuté části zůstávají součástí dokumentu. Pokud je true, oříznuté části budou odstraněny, pokud je false, budou v dokumentu serializovány (což může vést k většímu souboru)

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

True pro vyloučení atributů šířky a výšky ze svg kontejneru – to učiní rozvržení responzivním. False – jinak. Čtení/Zápis boolean.

**Vrací:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

True pro vyloučení atributů šířky a výšky ze svg kontejneru – to učiní rozvržení responzivním. False – jinak. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |