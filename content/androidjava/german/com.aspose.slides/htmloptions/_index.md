---
title: HtmlOptions
second_title: Aspose.Slides für Android über die Java API-Referenz
description: Stellt Optionen für den HTML-Export dar.
type: docs
url: /de/com.aspose.slides/htmloptions/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

Stellt Optionen für den HTML-Export dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Erstellt ein neues HtmlOptions-Objekt, das einen Callback spezifiziert. |
| [HtmlOptions()](#HtmlOptions--) | Erstellt ein neues HtmlOptions-Objekt zum Speichern in einer einzelnen HTML-Datei. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Liest oder legt den Modus fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite angeordnet werden. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Liest oder legt den Modus fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite angeordnet werden. |
| [getInkOptions()](#getInkOptions--) | Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. |
| [getHtmlFormatter()](#getHtmlFormatter--) | Liest oder legt die HTML-Vorlage fest. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Liest oder legt die HTML-Vorlage fest. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Liest oder legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Liest oder legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Liest oder legt die Optionen für das Folienbildformat fest. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Liest oder legt die Optionen für das Folienbildformat fest. |
| [getJpegQuality()](#getJpegQuality--) | Liest oder legt einen Wert fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Liest oder legt einen Wert fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. |
| [getPicturesCompression()](#getPicturesCompression--) | Stellt das Komprimierungsniveau für Bilder dar |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Stellt das Komprimierungsniveau für Bilder dar |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Ein boolesches Flag gibt an, ob die zugeschnittenen Teile Teil des Dokuments bleiben. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Ein boolesches Flag gibt an, ob die zugeschnittenen Teile Teil des Dokuments bleiben. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | Wahr, um die Breiten- und Höhenattribute vom SVG-Container auszuschließen – dadurch wird das Layout responsiv. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | Wahr, um die Breiten- und Höhenattribute vom SVG-Container auszuschließen – dadurch wird das Layout responsiv. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```


Erstellt ein neues HtmlOptions-Objekt, das einen Callback spezifiziert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Callback-Objekt, das das Speichern des Projekts steuert. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```


Erstellt ein neues HtmlOptions-Objekt zum Speichern in einer einzelnen HTML-Datei.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Liest oder legt den Modus fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite angeordnet werden.

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

**Rückgabewert:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Liest oder legt den Modus fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite angeordnet werden.

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
public final IInkOptions getInkOptions()
```


Stellt Optionen bereit, die das Aussehen von Ink-Objekten im exportierten Dokument steuern. Nur-Lesen [IInkOptions](../../com.aspose.slides/iinkoptions)

**Rückgabewert:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standardwert ist false.

**Rückgabewert:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Gibt an, ob das erzeugte Dokument versteckte Folien enthalten soll oder nicht. Standardwert ist false.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```


Liest oder legt die HTML-Vorlage fest. Lesen/Schreiben [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Rückgabewert:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```


Liest oder legt die HTML-Vorlage fest. Lesen/Schreiben [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


Liest oder legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. Wird er auf true gesetzt, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

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

**Rückgabewert:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```


Liest oder legt einen Wert fest, der angibt, ob Text ohne Ligaturen gerendert wird. Wird er auf true gesetzt, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

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

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```


Liest oder legt die Optionen für das Folienbildformat fest. Lesen/Schreiben [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Rückgabewert:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```


Liest oder legt die Optionen für das Folienbildformat fest. Lesen/Schreiben [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```


Liest oder legt einen Wert fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lesen/Schreiben byte.

--------------------

Wirkt nur, wenn ein Dokument JPEG-Bilder enthält.

Verwenden Sie diese Eigenschaft, um die Qualität der Bilder in einem Dokument beim Speichern im PDF-Format zu erhalten oder festzulegen. Der Wert kann von 0 bis 100 variieren, wobei 0 die schlechteste Qualität bei maximaler Kompression bedeutet und 100 die beste Qualität bei minimaler Kompression.

Der Standardwert ist **95**.

**Rückgabewert:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```


Liest oder legt einen Wert fest, der die Qualität der JPEG-Bilder im PDF-Dokument bestimmt. Lesen/Schreiben byte.

--------------------

Wirkt nur, wenn ein Dokument JPEG-Bilder enthält.

Verwenden Sie diese Eigenschaft, um die Qualität der Bilder in einem Dokument beim Speichern im PDF-Format zu erhalten oder festzulegen. Der Wert kann von 0 bis 100 variieren, wobei 0 die schlechteste Qualität bei maximaler Kompression bedeutet und 100 die beste Qualität bei minimaler Kompression.

Der Standardwert ist **95**.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```


Stellt das Komprimierungsniveau für Bilder dar

**Rückgabewert:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```


Stellt das Komprimierungsniveau für Bilder dar

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```


Ein boolesches Flag gibt an, ob die zugeschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die zugeschnittenen Teile entfernt, andernfalls bleiben sie im Dokument (was zu einer größeren Datei führen kann)

**Rückgabewert:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```


Ein boolesches Flag gibt an, ob die zugeschnittenen Teile Teil des Dokuments bleiben. Wenn true, werden die zugeschnittenen Teile entfernt, andernfalls bleiben sie im Dokument (was zu einer größeren Datei führen kann)

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```


Wahr, um die Breiten- und Höhenattribute vom SVG-Container auszuschließen – dadurch wird das Layout responsiv. Falsch – sonst. Lesen/Schreiben boolesch.

**Rückgabewert:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```


Wahr, um die Breiten- und Höhenattribute vom SVG-Container auszuschließen – dadurch wird das Layout responsiv. Falsch – sonst. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |