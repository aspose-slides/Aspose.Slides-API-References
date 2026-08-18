---
title: IHtmlOptions
second_title: Referencja API Aspose.Slides dla Javy
description: Reprezentuje opcje eksportu HTML.
type: docs
url: /pl/com.aspose.slides/ihtmloptions/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

Reprezentuje opcje eksportu HTML.
## Metody

| Metoda | Opis |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | Zwraca lub ustawia szablon HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Zwraca lub ustawia szablon HTML. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Zwraca lub ustawia opcje formatu obrazu slajdu. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Zwraca lub ustawia opcje formatu obrazu slajdu. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. |
| [getJpegQuality()](#getJpegQuality--) | Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Reprezentuje poziom kompresji obrazów Odczyt/zapis [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Reprezentuje poziom kompresji obrazów Odczyt/zapis [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Flaga logiczna wskazuje, czy przycięte części pozostają częścią dokumentu. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Flaga logiczna wskazuje, czy przycięte części pozostają częścią dokumentu. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True aby wykluczyć atrybuty width i height z kontenera SVG — to sprawi, że układ będzie responsywny. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True aby wykluczyć atrybuty width i height z kontenera SVG — to sprawi, że układ będzie responsywny. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Zwraca lub ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Zwraca lub ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Zwraca lub ustawia tryb, w którym slajdy są rozmieszczane na stronie przy eksportowaniu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Zwraca lub ustawia tryb, w którym slajdy są rozmieszczane na stronie przy eksportowaniu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

Zwraca lub ustawia szablon HTML. Odczyt/zapis [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Zwraca:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

Zwraca lub ustawia szablon HTML. Odczyt/zapis [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

Zwraca lub ustawia opcje formatu obrazu slajdu. Odczyt/zapis [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Zwraca:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

Zwraca lub ustawia opcje formatu obrazu slajdu. Odczyt/zapis [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. Domyślnie false.

**Zwraca:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Określa, czy wygenerowany dokument powinien zawierać ukryte slajdy, czy nie. Domyślnie false.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. Odczyt/zapis byte.

--------------------

Ma efekt tylko wtedy, gdy dokument zawiera obrazy JPEG.

Użyj tej właściwości, aby odczytać lub ustawić jakość obrazów w dokumencie przy zapisie w formacie PDF. Wartość może wynosić od 0 do 100, gdzie 0 oznacza najgorszą jakość przy maksymalnej kompresji, a 100 najlepszą jakość przy minimalnej kompresji.

Domyślna wartość to **95**.

**Zwraca:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Zwraca lub ustawia wartość określającą jakość obrazów JPEG w dokumencie PDF. Odczyt/zapis byte.

--------------------

Ma efekt tylko wtedy, gdy dokument zawiera obrazy JPEG.

Użyj tej właściwości, aby odczytać lub ustawić jakość obrazów w dokumencie przy zapisie w formacie PDF. Wartość może wynosić od 0 do 100, gdzie 0 oznacza najgorszą jakość przy maksymalnej kompresji, a 100 najlepszą jakość przy minimalnej kompresji.

Domyślna wartość to **95**.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Reprezentuje poziom kompresji obrazów Odczyt/zapis [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Zwraca:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Reprezentuje poziom kompresji obrazów Odczyt/zapis [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Flaga logiczna wskazuje, czy przycięte części pozostają częścią dokumentu. Jeśli true, przycięte części zostaną usunięte; jeśli false, będą serializowane w dokumencie (co może prowadzić do większego pliku). Odczyt/zapis boolean.

**Zwraca:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Flaga logiczna wskazuje, czy przycięte części pozostają częścią dokumentu. Jeśli true, przycięte części zostaną usunięte; jeśli false, będą serializowane w dokumencie (co może prowadzić do większego pliku). Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

True aby wykluczyć atrybuty width i height z kontenera SVG — to sprawi, że układ będzie responsywny. False — w przeciwnym razie. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

True aby wykluczyć atrybuty width i height z kontenera SVG — to sprawi, że układ będzie responsywny. False — w przeciwnym razie. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Zwraca lub ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie, ta właściwość ma wartość false.

--------------------

> ```
> Przykład:
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
public abstract void setDisableFontLigatures(boolean value)
```

Zwraca lub ustawia wartość wskazującą, czy tekst jest renderowany bez użycia ligatur. Gdy ustawione na true, ligatury będą wyłączone w renderowanym wyjściu. Domyślnie, ta właściwość ma wartość false.

--------------------

> ```
> Przykład:
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

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Zwraca lub ustawia tryb, w którym slajdy są rozmieszczane na stronie przy eksportowaniu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Przykład:
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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Zwraca lub ustawia tryb, w którym slajdy są rozmieszczane na stronie przy eksportowaniu prezentacji [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Przykład:
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
public abstract IInkOptions getInkOptions()
```

Udostępnia opcje kontrolujące wygląd obiektów Ink w wyeksportowanym dokumencie. Tylko do odczytu [IInkOptions](../../com.aspose.slides/iinkoptions)

**Zwraca:**
[IInkOptions](../../com.aspose.slides/iinkoptions)