---
title: IHtml5Options
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt HTML5-Exportoptionen dar.
type: docs
url: /de/com.aspose.slides/ihtml5options/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtml5Options extends ISaveOptions
```

Stellt HTML5-Exportoptionen dar.

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
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | Gibt die Übergangsanimationsoption zurück oder legt sie fest. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | Gibt die Übergangsanimationsoption zurück oder legt sie fest. |
| [getAnimateShapes()](#getAnimateShapes--) | Gibt die Formenanimationsoption zurück oder legt sie fest. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | Gibt die Formenanimationsoption zurück oder legt sie fest. |
| [getEmbedImages()](#getEmbedImages--) | Gibt die Bild-Einbettungsoption zurück oder legt sie fest. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | Gibt die Bild-Einbettungsoption zurück oder legt sie fest. |
| [getOutputPath()](#getOutputPath--) | Bestimmt, wo externe Ressourcen gespeichert werden sollen. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | Bestimmt, wo externe Ressourcen gespeichert werden sollen. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Gibt einen Wert zurück oder legt ihn fest, der angibt, ob Text ohne Ligaturen gerendert wird. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Gibt einen Wert zurück oder legt ihn fest, der angibt, ob Text ohne Ligaturen gerendert wird. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Gibt den Modus zurück oder legt ihn fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite angeordnet werden. |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Gibt den Modus zurück oder legt ihn fest, in dem Folien beim Export einer Präsentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) auf der Seite angeordnet werden. |

### getAnimateTransitions() {#getAnimateTransitions--}
```
public abstract boolean getAnimateTransitions()
```

Gibt die Übergangsanimationsoption zurück oder legt sie fest. Lese-/Schreibzugriff boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**  
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public abstract void setAnimateTransitions(boolean value)
```

Gibt die Übergangsanimationsoption zurück oder legt sie fest. Lese-/Schreibzugriff boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
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
public abstract boolean getAnimateShapes()
```

Gibt die Formenanimationsoption zurück oder legt sie fest. Lese-/Schreibzugriff boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**  
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public abstract void setAnimateShapes(boolean value)
```

Gibt die Formenanimationsoption zurück oder legt sie fest. Lese-/Schreibzugriff boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
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
public abstract boolean getEmbedImages()
```

Gibt die Bild-Einbettungsoption zurück oder legt sie fest. Lese-/Schreibzugriff boolean.

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

**Rückgabe:**  
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public abstract void setEmbedImages(boolean value)
```

Gibt die Bild-Einbettungsoption zurück oder legt sie fest. Lese-/Schreibzugriff boolean.

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
public abstract String getOutputPath()
```

Bestimmt, wo externe Ressourcen gespeichert werden sollen. Lese-/Schreibzugriff String.

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

**Rückgabe:**  
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public abstract void setOutputPath(String value)
```

Bestimmt, wo externe Ressourcen gespeichert werden sollen. Lese-/Schreibzugriff String.

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

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Gibt einen Wert zurück oder legt ihn fest, der angibt, ob Text ohne Ligaturen gerendert wird. Bei true werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Ligaturen in der Textdarstellung deaktivieren
> 
>      pres.save("output.html", SaveFormat.Html5, options);
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

Gibt einen Wert zurück oder legt ihn fest, der angibt, ob Text ohne Ligaturen gerendert wird. Bei true werden Ligaturen in der Ausgabe deaktiviert. Standardmäßig ist diese Eigenschaft auf false gesetzt.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Ligaturen in der Textdarstellung deaktivieren
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
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
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

**Rückgabe:**  
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
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