---
title: Html5Options
second_title: Referencia de API de Aspose.Slides para Java
description: Representa opciones de exportación HTML5.
type: docs
url: /es/com.aspose.slides/html5options/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas las Interfaces Implementadas:**
[com.aspose.slides.IHtml5Options](../../com.aspose.slides/ihtml5options)
```
public class Html5Options extends SaveOptions implements IHtml5Options
```

Representa opciones de exportación HTML5.

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
## Constructors

| Constructor | Description |
| --- | --- |
| [Html5Options()](#Html5Options--) | Default constructor. |
## Methods

| Method | Description |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | Returns or sets transitions animation option. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | Returns or sets transitions animation option. |
| [getAnimateShapes()](#getAnimateShapes--) | Returns or sets shapes animation option. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | Returns or sets shapes animation option. |
| [getEmbedImages()](#getEmbedImages--) | Returns or sets images embedding option. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | Returns or sets images embedding option. |
| [getOutputPath()](#getOutputPath--) | Determines where external resources should be stored. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | Determines where external resources should be stored. |
| [getPicturesCompression()](#getPicturesCompression--) | Represents the pictures compression level |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Represents the pictures compression level |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Gets or sets a value indicating whether text is rendered without using ligatures. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Gets or sets a value indicating whether text is rendered without using ligatures. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### Html5Options() {#Html5Options--}
```
public Html5Options()
```

Default constructor.

### getAnimateTransitions() {#getAnimateTransitions--}
```
public final boolean getAnimateTransitions()
```

Devuelve o establece la opción de animación de transiciones. Booleano de lectura/escritura.

--------------------

> ```
> Ejemplo:
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

**Returns:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public final void setAnimateTransitions(boolean value)
```

Devuelve o establece la opción de animación de transiciones. Booleano de lectura/escritura.

--------------------

> ```
> Ejemplo:
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public final boolean getAnimateShapes()
```

Devuelve o establece la opción de animación de formas. Booleano de lectura/escritura.

--------------------

> ```
> Ejemplo:
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

**Returns:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public final void setAnimateShapes(boolean value)
```

Devuelve o establece la opción de animación de formas. Booleano de lectura/escritura.

--------------------

> ```
> Ejemplo:
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public final boolean getEmbedImages()
```

Devuelve o establece la opción de incrustación de imágenes. Booleano de lectura/escritura.

--------------------

> ```
> Ejemplo:
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

**Returns:**
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public final void setEmbedImages(boolean value)
```

Returns or sets images embedding option. Read/write boolean.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public final String getOutputPath()
```

Determina dónde se deben almacenar los recursos externos. String de lectura/escritura.

--------------------

> ```
> Ejemplo:
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
```
public final void setOutputPath(String value)
```

Determina dónde se deben almacenar los recursos externos. String de lectura/escritura.

--------------------

> ```
> Ejemplo:
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Represents the pictures compression level

**Returns:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Represents the pictures compression level

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```
Gets or sets a value indicating whether text is rendered without using ligatures. When set to true, ligatures will be disabled in the rendered output. By default, this property is set to false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Desactivar ligaduras en el renderizado de texto
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
```
public final void setDisableFontLigatures(boolean value)
```
Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en true, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está establecida en false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Desactivar ligaduras en el renderizado de texto
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Gets or sets the mode in which slides are placed on the page when exporting a presentation [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Returns:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)


Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Ejemplo:
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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |