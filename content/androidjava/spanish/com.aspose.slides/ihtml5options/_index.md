---
title: IHtml5Options
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa una opción de exportación HTML5.
type: docs
url: /es/com.aspose.slides/ihtml5options/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtml5Options extends ISaveOptions
```

Representa una opción de exportación HTML5.

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
## Métodos

| Método | Descripción |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | Devuelve o establece la opción de animación de transiciones. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | Devuelve o establece la opción de animación de transiciones. |
| [getAnimateShapes()](#getAnimateShapes--) | Devuelve o establece la opción de animación de formas. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | Devuelve o establece la opción de animación de formas. |
| [getEmbedImages()](#getEmbedImages--) | Devuelve o establece la opción de incrustación de imágenes. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | Devuelve o establece la opción de incrustación de imágenes. |
| [getOutputPath()](#getOutputPath--) | Determina dónde se deben almacenar los recursos externos. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | Determina dónde se deben almacenar los recursos externos. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Obtiene o establece un valor que indica si el texto se representa sin usar ligaduras. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Obtiene o establece un valor que indica si el texto se representa sin usar ligaduras. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getAnimateTransitions() {#getAnimateTransitions--}
```
public abstract boolean getAnimateTransitions()
```

Devuelve o establece la opción de animación de transiciones. Lectura/escritura booleano.

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

**Devuelve:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public abstract void setAnimateTransitions(boolean value)
```

Devuelve o establece la opción de animación de transiciones. Lectura/escritura booleano.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public abstract boolean getAnimateShapes()
```

Devuelve o establece la opción de animación de formas. Lectura/escritura booleano.

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

**Devuelve:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public abstract void setAnimateShapes(boolean value)
```

Devuelve o establece la opción de animación de formas. Lectura/escritura booleano.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public abstract boolean getEmbedImages()
```

Devuelve o establece la opción de incrustación de imágenes. Lectura/escritura booleano.

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

**Devuelve:**
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public abstract void setEmbedImages(boolean value)
```

Devuelve o establece la opción de incrustación de imágenes. Lectura/escritura booleano.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public abstract String getOutputPath()
```

Determina dónde se deben almacenar los recursos externos. Lectura/escritura String.

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

**Devuelve:**
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public abstract void setOutputPath(String value)
```

Determina dónde se deben almacenar los recursos externos. Lectura/escritura String.

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Obtiene o establece un valor que indica si el texto se representa sin usar ligaduras. Cuando se establece en true, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad tiene el valor false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Desactivar ligaduras en la representación de texto
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Obtiene o establece un valor que indica si el texto se representa sin usar ligaduras. Cuando se establece en true, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad tiene el valor false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Desactivar ligaduras en la representación de texto
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Devuelve:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |