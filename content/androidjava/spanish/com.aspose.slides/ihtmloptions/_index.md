---
title: IHtmlOptions
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa opciones de exportación HTML.
type: docs
url: /es/com.aspose.slides/ihtmloptions/
---
**Todas las Interfaces Implementadas:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

Representa opciones de exportación HTML.
## Métodos

| Método | Descripción |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | Devuelve o establece la plantilla HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Devuelve o establece la plantilla HTML. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Devuelve o establece las opciones de formato de imagen de diapositiva. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Devuelve o establece las opciones de formato de imagen de diapositiva. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Especifica si el documento generado debe incluir diapositivas ocultas o no. |
| [getJpegQuality()](#getJpegQuality--) | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Representa el nivel de compresión de imágenes Lectura/escritura [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Representa el nivel de compresión de imágenes Lectura/escritura [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Una bandera booleana indica si las partes recortadas permanecen como parte del documento. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Una bandera booleana indica si las partes recortadas permanecen como parte del documento. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | True para excluir los atributos de ancho y alto del contenedor SVG - eso hará que el diseño sea responsivo. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | True para excluir los atributos de ancho y alto del contenedor SVG - eso hará que el diseño sea responsivo. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

Devuelve o establece la plantilla HTML. Lectura/escritura [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Devuelve:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

Devuelve o establece la plantilla HTML. Lectura/escritura [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

Devuelve o establece las opciones de formato de imagen de diapositiva. Lectura/escritura [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Devuelve:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

Devuelve o establece las opciones de formato de imagen de diapositiva. Lectura/escritura [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Devuelve:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Especifica si el documento generado debe incluir diapositivas ocultas o no. El valor predeterminado es false.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Lectura/escritura byte.

--------------------

Solo tiene efecto cuando un documento contiene imágenes JPEG.

Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.

The default value is **95**.

**Devuelve:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Devuelve o establece un valor que determina la calidad de las imágenes JPEG dentro del documento PDF. Lectura/escritura byte.

--------------------

Solo tiene efecto cuando un documento contiene imágenes JPEG.

Use this property to get or set the quality of the images inside a document when saving in PDF format. The value may vary from 0 to 100 where 0 means worst quality but maximum compression and 100 means best quality but minimum compression.

The default value is **95**.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Representa el nivel de compresión de imágenes Lectura/escritura [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Devuelve:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Representa el nivel de compresión de imágenes Lectura/escritura [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Una bandera booleana indica si las partes recortadas permanecen como parte del documento. Si es true, las partes recortadas serán eliminadas; si es false, se serializarán en el documento (lo que puede conducir a un archivo más grande). Lectura/escritura boolean.

**Devuelve:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Una bandera booleana indica si las partes recortadas permanecen como parte del documento. Si es true, las partes recortadas serán eliminadas; si es false, se serializarán en el documento (lo que puede conducir a un archivo más grande). Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

True para excluir los atributos de ancho y alto del contenedor SVG - eso hará que el diseño sea responsivo. False - en caso contrario. Lectura/escritura boolean.

**Devuelve:**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

True para excluir los atributos de ancho y alto del contenedor SVG - eso hará que el diseño sea responsivo. False - en caso contrario. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en true, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está establecida en false.

--------------------

> ```
> Ejemplo:
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
public abstract void setDisableFontLigatures(boolean value)
```

Obtiene o establece un valor que indica si el texto se renderiza sin usar ligaduras. Cuando se establece en true, las ligaduras se desactivarán en la salida renderizada. Por defecto, esta propiedad está establecida en false.

--------------------

> ```
> Ejemplo:
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

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Ejemplo:
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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Obtiene o establece el modo en que las diapositivas se colocan en la página al exportar una presentación [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Ejemplo:
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
public abstract IInkOptions getInkOptions()
```

Proporciona opciones que controlan la apariencia de los objetos Ink en el documento exportado. Solo lectura [IInkOptions](../../com.aspose.slides/iinkoptions)

**Devuelve:**
[IInkOptions](../../com.aspose.slides/iinkoptions)