---
title: Html5Options
second_title: Aspose.Slides für Java API-Referenz
description: Stellt Optionen für den HTML5-Export dar.
type: docs
url: /de/com.aspose.slides/html5options/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IHtml5Options](../../com.aspose.slides/ihtml5options)
```
public class Html5Options extends SaveOptions implements IHtml5Options
```

Stellt Optionen für den HTML5-Export dar.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Html5Options()](#Html5Options--) | Standardkonstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | Gibt die Option für die Übergangsanimation zurück oder setzt sie. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | Gibt die Option für die Übergangsanimation zurück oder setzt sie. |
| [getAnimateShapes()](#getAnimateShapes--) | Gibt die Option für die Formanimation zurück oder setzt sie. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | Gibt die Option für die Formanimation zurück oder setzt sie. |
| [getEmbedImages()](#getEmbedImages--) | Gibt die Option für das Einbetten von Bildern zurück oder setzt sie. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | Gibt die Option für das Einbetten von Bildern zurück oder setzt sie. |
| [getOutputPath()](#getOutputPath--) | Bestimmt, wo externe Ressourcen gespeichert werden sollen. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | Bestimmt, wo externe Ressourcen gespeichert werden sollen. |
| [getPicturesCompression()](#getPicturesCompression--) | Stellt die Komprimierungsstufe für Bilder dar |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Stellt die Komprimierungsstufe für Bilder dar |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Gibt einen Wert zurück oder legt ihn fest, der angibt, ob Text ohne Ligaturen dargestellt wird. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Gibt einen Wert zurück oder legt ihn fest, der angibt, ob Text ohne Ligaturen dargestellt wird. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Gibt den Modus zurück oder legt ihn fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite angeordnet werden. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Gibt den Modus zurück oder legt ihn fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite angeordnet werden. |
### Html5Options() {#Html5Options--}
```
public Html5Options()
```


Standardkonstruktor.

### getAnimateTransitions() {#getAnimateTransitions--}
```
public final boolean getAnimateTransitions()
```


Gibt die Option für die Übergangsanimation zurück oder setzt sie. Lesen/Schreiben boolesch.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public final void setAnimateTransitions(boolean value)
```


Gibt die Option für die Übergangsanimation zurück oder setzt sie. Lesen/Schreiben boolesch.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public final boolean getAnimateShapes()
```


Gibt die Option für die Formanimation zurück oder setzt sie. Lesen/Schreiben boolesch.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public final void setAnimateShapes(boolean value)
```


Gibt die Option für die Formanimation zurück oder setzt sie. Lesen/Schreiben boolesch.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public final boolean getEmbedImages()
```


Gibt die Option für das Einbetten von Bildern zurück oder setzt sie. Lesen/Schreiben boolesch.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public final void setEmbedImages(boolean value)
```


Gibt die Option für das Einbetten von Bildern zurück oder setzt sie. Lesen/Schreiben boolesch.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public final String getOutputPath()
```


Bestimmt, wo externe Ressourcen gespeichert werden sollen. Lesen/Schreiben String.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabewert:**
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public final void setOutputPath(String value)
```


Bestimmt, wo externe Ressourcen gespeichert werden sollen. Lesen/Schreiben String.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```


Stellt die Komprimierungsstufe für Bilder dar

**Rückgabewert:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```


Stellt die Komprimierungsstufe für Bilder dar

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


Gibt einen Wert zurück oder legt ihn fest, der angibt, ob Text ohne Ligaturen dargestellt wird. Wird auf true gesetzt, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Ligaturen bei der Textdarstellung deaktivieren
> 
>      pres.save("output.html", SaveFormat.Html5, options);
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


Gibt einen Wert zurück oder legt ihn fest, der angibt, ob Text ohne Ligaturen dargestellt wird. Wird auf true gesetzt, werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Ligaturen bei der Textdarstellung deaktivieren
> 
>      pres.save("output.html", SaveFormat.Html5, options);
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
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Gibt den Modus zurück oder legt ihn fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite angeordnet werden.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
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


Gibt den Modus zurück oder legt ihn fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite angeordnet werden.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |