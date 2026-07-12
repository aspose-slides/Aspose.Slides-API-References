---
title: IHtmlOptions
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt Optionen für den HTML-Export dar.
type: docs
url: /de/com.aspose.slides/ihtmloptions/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

Stellt Optionen für den HTML-Export dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | Gibt das HTML-Template zurück oder legt es fest. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Gibt das HTML-Template zurück oder legt es fest. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Gibt die Optionen für das Folienbildformat zurück oder legt sie fest. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Gibt die Optionen für das Folienbildformat zurück oder legt sie fest. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. |
| [getJpegQuality()](#getJpegQuality--) | Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. |
| [getPicturesCompression()](#getPicturesCompression--) | Stellt das Komprimierungsniveau der Bilder dar Lese/Schreiben [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Stellt das Komprimierungsniveau der Bilder dar Lese/Schreiben [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True, um Breiten- und Höhenattribute aus dem SVG-Container zu entfernen – das macht das Layout responsiv. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True, um Breiten- und Höhenattribute aus dem SVG-Container zu entfernen – das macht das Layout responsiv. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Liest oder legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Liest oder legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Liest oder legt den Modus fest, in dem Folien auf der Seite platziert werden, wenn eine Präsentation exportiert wird [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Liest oder legt den Modus fest, in dem Folien auf der Seite platziert werden, wenn eine Präsentation exportiert wird [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

Gibt das HTML-Template zurück oder legt es fest. Lese/Schreiben [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Rückgabe:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

Gibt das HTML-Template zurück oder legt es fest. Lese/Schreiben [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

Gibt die Optionen für das Folienbildformat zurück oder legt sie fest. Lese/Schreiben [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Rückgabe:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

Gibt die Optionen für das Folienbildformat zurück oder legt sie fest. Lese/Schreiben [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. Standardwert ist false.

**Rückgabe:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Gibt an, ob das erzeugte Dokument verborgene Folien enthalten soll oder nicht. Standardwert ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lese/Schreiben byte.

--------------------

Wirkt nur, wenn ein Dokument JPEG-Bilder enthält.

Verwenden Sie diese Eigenschaft, um die Qualität der Bilder im Dokument beim Speichern im PDF-Format zu erhalten oder festzulegen. Der Wert kann von 0 bis 100 variieren, wobei 0 die schlechteste Qualität bei maximaler Kompression bedeutet und 100 die beste Qualität bei minimaler Kompression.

Der Standardwert ist **95**.

**Rückgabe:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Gibt einen Wert zurück oder legt ihn fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lese/Schreiben byte.

--------------------

Wirkt nur, wenn ein Dokument JPEG-Bilder enthält.

Verwenden Sie diese Eigenschaft, um die Qualität der Bilder im Dokument beim Speichern im PDF-Format zu erhalten oder festzulegen. Der Wert kann von 0 bis 100 variieren, wobei 0 die schlechteste Qualität bei maximaler Kompression bedeutet und 100 die beste Qualität bei minimaler Kompression.

Der Standardwert ist **95**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Stellt das Komprimierungsniveau der Bilder dar Lese/Schreiben [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Rückgabe:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Stellt das Komprimierungsniveau der Bilder dar Lese/Schreiben [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die beschnittenen Teile entfernt, wenn false, bleiben sie im Dokument serialisiert (was zu einer größeren Datei führen kann) Lese/Schreiben boolean.

**Rückgabe:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Ein boolesches Flag gibt an, ob die beschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die beschnittenen Teile entfernt, wenn false, bleiben sie im Dokument serialisiert (was zu einer größeren Datei führen kann) Lese/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

True, um Breiten- und Höhenattribute aus dem SVG-Container zu entfernen – das macht das Layout responsiv. False – sonst. Lese/Schreiben boolean.

**Rückgabe:**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

True, um Breiten- und Höhenattribute aus dem SVG-Container zu entfernen – das macht das Layout responsiv. False – sonst. Lese/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Liest oder legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn true, werden Ligaturen im gerenderten Output deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

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


**Rückgabe:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Liest oder legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. Wenn true, werden Ligaturen im gerenderten Output deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Liest oder legt den Modus fest, in dem Folien auf der Seite platziert werden, wenn eine Präsentation exportiert wird [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Rückgabe:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Liest oder legt den Modus fest, in dem Folien auf der Seite platziert werden, wenn eine Präsentation exportiert wird [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Schreibgeschützt [IInkOptions](../../com.aspose.slides/iinkoptions)

**Rückgabe:**
[IInkOptions](../../com.aspose.slides/iinkoptions)