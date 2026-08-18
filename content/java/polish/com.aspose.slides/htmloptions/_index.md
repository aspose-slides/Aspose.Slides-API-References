---
title: HtmlOptions
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje opcje eksportu HTML.
type: docs
url: /pl/com.aspose.slides/htmloptions/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

Reprezentuje opcje eksportu HTML.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Tworzy nowy obiekt HtmlOptions określający wywołanie zwrotne. |
| [HtmlOptions()](#HtmlOptions--) | Tworzy nowy obiekt HtmlOptions do zapisywania w jednym pliku HTML. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. |
| [getHtmlFormatter()](#getHtmlFormatter--) | Zwraca lub ustawia szablon HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Zwraca lub ustawia szablon HTML. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Pobiera lub ustawia wartość określającą, czy tekst jest renderowany bez użycia ligatur. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Pobiera lub ustawia wartość określającą, czy tekst jest renderowany bez użycia ligatur. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Zwraca lub ustawia opcje formatu obrazu slajdu. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Zwraca lub ustawia opcje formatu obrazu slajdu. |
| [getJpegQuality()](#getJpegQuality--) | Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Reprezentuje poziom kompresji obrazków. |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Reprezentuje poziom kompresji obrazków. |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Flaga logiczna wskazuje, czy przycięte części pozostają częścią dokumentu. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Flaga logiczna wskazuje, czy przycięte części pozostają częścią dokumentu. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True, aby wykluczyć atrybuty width i height z kontenera svg — to sprawi, że układ będzie responsywny. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True, aby wykluczyć atrybuty width i height z kontenera svg — to sprawi, że układ będzie responsywny. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

Tworzy nowy obiekt HtmlOptions określający wywołanie zwrotne.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Obiekt wywołania zwrotnego kontrolujący zapisywanie projektu. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

Tworzy nowy obiekt HtmlOptions do zapisywania w jednym pliku HTML.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Zwraca:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Pobiera lub ustawia tryb, w którym slajdy są rozmieszczane na stronie podczas eksportu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. Tylko do odczytu [IInkOptions](../../com.aspose.slides/iinkoptions)

**Zwraca:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. Domyślnie false.

**Zwraca:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Określa, czy wygenerowany dokument ma zawierać ukryte slajdy. Domyślnie false.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

Zwraca lub ustawia szablon HTML. Odczyt/zapis [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Zwraca:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

Zwraca lub ustawia szablon HTML. Odczyt/zapis [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Pobiera lub ustawia wartość określającą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury będą wyłączone w renderowanym wyniku. Domyślnie właściwość ma wartość false.

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

**Zwraca:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

Pobiera lub ustawia wartość określającą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury będą wyłączone w renderowanym wyniku. Domyślnie właściwość ma wartość false.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

Zwraca lub ustawia opcje formatu obrazu slajdu. Odczyt/zapis [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Zwraca:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

Zwraca lub ustawia opcje formatu obrazu slajdu. Odczyt/zapis [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. Odczyt/zapis byte.

--------------------
Ma wpływ tylko wtedy, gdy dokument zawiera obrazy JPEG.

Użyj tej właściwości, aby pobrać lub ustawić jakość obrazów w dokumencie przy zapisywaniu w formacie PDF. Wartość może wynosić od 0 do 100, gdzie 0 oznacza najgorszą jakość przy maksymalnej kompresji, a 100 najlepszą jakość przy minimalnej kompresji.

Domyślna wartość to **95**.

**Zwraca:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. Odczyt/zapis byte.

--------------------
Ma wpływ tylko wtedy, gdy dokument zawiera obrazy JPEG.

Użyj tej właściwości, aby pobrać lub ustawić jakość obrazów w dokumencie przy zapisywaniu w formacie PDF. Wartość może wynosić od 0 do 100, gdzie 0 oznacza najgorszą jakość przy maksymalnej kompresji, a 100 najlepszą jakość przy minimalnej kompresji.

Domyślna wartość to **95**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Reprezentuje poziom kompresji obrazków

**Zwraca:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Reprezentuje poziom kompresji obrazków

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Flaga logiczna wskazuje, czy przycięte części pozostają częścią dokumentu. Jeśli true, przycięte części zostaną usunięte, jeśli false, zostaną zserializowane w dokumencie (co może prowadzić do większego pliku)

**Zwraca:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Flaga logiczna wskazuje, czy przycięte części pozostają częścią dokumentu. Jeśli true, przycięte części zostaną usunięte, jeśli false, zostaną zserializowane w dokumencie (co może prowadzić do większego pliku)

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

True, aby wykluczyć atrybuty width i height z kontenera svg — spowoduje to responsywny układ. False w przeciwnym wypadku. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

True, aby wykluczyć atrybuty width i height z kontenera svg — spowoduje to responsywny układ. False w przeciwnym wypadku. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |