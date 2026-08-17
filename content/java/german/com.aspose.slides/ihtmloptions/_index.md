---
title: IHtmlOptions
second_title: Aspose.Slides für Java API-Referenz
description: Stellt HTML-Exportoptionen dar.
type: docs
url: /de/com.aspose.slides/ihtmloptions/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

Stellt HTML-Exportoptionen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | Liefert oder setzt das HTML-Template. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Liefert oder setzt das HTML-Template. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Liefert oder setzt die Optionen für das Folienbildformat. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Liefert oder setzt die Optionen für das Folienbildformat. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. |
| [getJpegQuality()](#getJpegQuality--) | Liefert oder setzt einen Wert, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Liefert oder setzt einen Wert, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. |
| [getPicturesCompression()](#getPicturesCompression--) | Stellt das Kompressionslevel für Bilder dar Lesen/Schreiben [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Stellt das Kompressionslevel für Bilder dar Lesen/Schreiben [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Ein boolesches Flag gibt an, ob die zugeschnittenen Teile Teil des Dokuments bleiben. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Ein boolesches Flag gibt an, ob die zugeschnittenen Teile Teil des Dokuments bleiben. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True, um Breiten- und Höhenattribute aus dem SVG-Container auszuschließen – das macht das Layout responsiv. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True, um Breiten- und Höhenattribute aus dem SVG-Container auszuschließen – das macht das Layout responsiv. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Liefert oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Liefert oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Liefert oder setzt den Modus, in dem Folien beim Export einer Präsentation auf der Seite angeordnet werden [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Liefert oder setzt den Modus, in dem Folien beim Export einer Präsentation auf der Seite angeordnet werden [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Bietet Optionen, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

Liefert oder setzt das HTML-Template. Lesen/Schreiben [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Rückgabe:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

Liefert oder setzt das HTML-Template. Lesen/Schreiben [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

Liefert oder setzt die Optionen für das Folienbildformat. Lesen/Schreiben [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Rückgabe:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

Liefert oder setzt die Optionen für das Folienbildformat. Lesen/Schreiben [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. Standard ist false.

**Rückgabe:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. Standard ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Liefert oder setzt einen Wert, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lesen/Schreiben byte.

--------------------

Wirkt nur, wenn ein Dokument JPEG-Bilder enthält.

Verwenden Sie diese Eigenschaft, um die Qualität der Bilder in einem Dokument beim Speichern im PDF-Format zu erhalten oder zu setzen. Der Wert kann von 0 bis 100 variieren, wobei 0 die schlechteste Qualität bei maximaler Kompression und 100 die beste Qualität bei minimaler Kompression bedeutet.

Der Standardwert ist **95**.

**Rückgabe:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Liefert oder setzt einen Wert, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lesen/Schreiben byte.

--------------------

Wirkt nur, wenn ein Dokument JPEG-Bilder enthält.

Verwenden Sie diese Eigenschaft, um die Qualität der Bilder in einem Dokument beim Speichern im PDF-Format zu erhalten oder zu setzen. Der Wert kann von 0 bis 100 variieren, wobei 0 die schlechteste Qualität bei maximaler Kompression und 100 die beste Qualität bei minimaler Kompression bedeutet.

Der Standardwert ist **95**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Stellt das Kompressionslevel für Bilder dar Lesen/Schreiben [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Rückgabe:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Stellt das Kompressionslevel für Bilder dar Lesen/Schreiben [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Ein boolesches Flag gibt an, ob die zugeschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die zugeschnittenen Teile entfernt, wenn false, werden sie im Dokument serialisiert (was zu einer größeren Datei führen kann) Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Ein boolesches Flag gibt an, ob die zugeschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die zugeschnittenen Teile entfernt, wenn false, werden sie im Dokument serialisiert (was zu einer größeren Datei führen kann) Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

True, um Breiten- und Höhenattribute aus dem SVG-Container auszuschließen – das macht das Layout responsiv. False – sonst. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

True, um Breiten- und Höhenattribute aus dem SVG-Container auszuschließen – das macht das Layout responsiv. False – sonst. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Liefert oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wird er auf true gesetzt, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

--------------------

> ```
> Beispiel:
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


**Rückgabe:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Liefert oder setzt einen Wert, der angibt, ob Text ohne Ligaturen gerendert wird. Wird er auf true gesetzt, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

--------------------

> ```
> Beispiel:
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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Liefert oder setzt den Modus, in dem Folien beim Export einer Präsentation auf der Seite angeordnet werden [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Beispiel:
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


**Rückgabe:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Liefert oder setzt den Modus, in dem Folien beim Export einer Präsentation auf der Seite angeordnet werden [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Beispiel:
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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Bietet Optionen, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Nur lesbar [IInkOptions](../../com.aspose.slides/iinkoptions)

**Rückgabe:**
[IInkOptions](../../com.aspose.slides/iinkoptions)