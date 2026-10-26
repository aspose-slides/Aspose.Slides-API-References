---
title: HtmlOptions
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa opciones de exportación HTML.
type: docs
url: /es/com.aspose.slides/htmloptions/
---
**Herencia:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Todas las interfaces implementadas:**  
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)  
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

Representa opciones de exportación HTML.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Crea un nuevo objeto HtmlOptions especificando el callback. |
| [HtmlOptions()](#HtmlOptions--) | Crea un nuevo objeto HtmlOptions para guardar en un solo archivo HTML. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [getHtmlFormatter()](#getHtmlFormatter--) | Devuelve o establece la plantilla HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Devuelve o establece la plantilla HTML. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Devuelve o establece opciones de formato de imagen de diapositiva. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Devuelve o establece opciones de formato de imagen de diapositiva. |
| [getJpegQuality()](#getJpegQuality--) | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Representa el nivel de compresión de imágenes |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Representa el nivel de compresión de imágenes |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Una bandera booleana indica si las partes recortadas permanecen como parte del documento. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Una bandera booleana indica si las partes recortadas permanecen como parte del documento. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | Verdadero para excluir los atributos width y height del contenedor svg - eso hará que el diseño sea responsivo. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | Verdadero para excluir los atributos width y height del contenedor svg - eso hará que el diseño sea responsivo. |

### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

Crea un nuevo objeto HtmlOptions especificando el callback.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Objeto de callback que controla el guardado del proyecto. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

Crea un nuevo objeto HtmlOptions para guardar en un solo archivo HTML.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Devuelve:**  
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. **Solo lectura** [IInkOptions](../../com.aspose.slides/iinkoptions)

**Devuelve:**  
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Devuelve:**  
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

Devuelve o establece la plantilla HTML. **Lectura/escritura** [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Devuelve:**  
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

Devuelve o establece la plantilla HTML. **Lectura/escritura** [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en true, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está establecida en false.

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

**Devuelve:**  
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
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
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

Devuelve o establece opciones de formato de imagen de diapositiva. **Lectura/escritura** [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Devuelve:**  
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

Devuelve o establece opciones de formato de imagen de diapositiva. **Lectura/escritura** [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. **Lectura/escritura** byte.

Solo tiene efecto cuando un documento contiene imágenes JPEG.

Use esta propiedad para obtener o establecer la calidad de las imágenes dentro de un documento al guardarlo en formato PDF. El valor puede variar de 0 a 100 donde 0 significa la peor calidad pero máxima compresión y 100 significa la mejor calidad pero mínima compresión.

El valor predeterminado es **95**.

**Devuelve:**  
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. **Lectura/escritura** byte.

Solo tiene efecto cuando un documento contiene imágenes JPEG.

Use esta propiedad para obtener o establecer la calidad de las imágenes dentro de un documento al guardarlo en formato PDF. El valor puede variar de 0 a 100 donde 0 significa la peor calidad pero máxima compresión y 100 significa la mejor calidad pero mínima compresión.

El valor predeterminado es **95**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Representa el nivel de compresión de imágenes

**Devuelve:**  
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Representa el nivel de compresión de imágenes

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Una bandera booleana indica si las partes recortadas permanecen como parte del documento. Si true, las partes recortadas serán eliminadas; si false, se serializarán en el documento (lo que puede generar un archivo más grande)

**Devuelve:**  
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Una bandera booleana indica si las partes recortadas permanecen como parte del documento. Si true, las partes recortadas serán eliminadas; si false, se serializarán en el documento (lo que puede generar un archivo más grande)

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

Verdadero para excluir los atributos width y height del contenedor svg - eso hará que el diseño sea responsivo. False - de lo contrario. **Lectura/escritura** boolean.

**Devuelve:**  
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

Verdadero para excluir los atributos width y height del contenedor svg - eso hará que el diseño sea responsivo. False - de lo contrario. **Lectura/escritura** boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |