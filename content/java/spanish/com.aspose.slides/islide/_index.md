---
title: ISlide
second_title: Referencia de API de Aspose.Slides para Java
description: Representa una diapositiva en una presentación.
type: docs
url: /es/com.aspose.slides/islide/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Representa una diapositiva en una presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Devuelve el administrador HeaderFooter de la diapositiva. |
| [getSlideNumber()](#getSlideNumber--) | Devuelve un número de diapositiva. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Devuelve un número de diapositiva. |
| [getHidden()](#getHidden--) | Determina si la diapositiva especificada está oculta durante una presentación. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determina si la diapositiva especificada está oculta durante una presentación. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Devuelve un objeto de imagen con escalado personalizado. |
| [getImage()](#getImage--) | Devuelve un objeto Thumbnail Image (20 % del tamaño real). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Devuelve un objeto de imagen con el tamaño especificado. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Devuelve un objeto Thumbnail tiff bitmap con los parámetros especificados. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Devuelve un objeto Thumbnail Bitmap. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Devuelve un objeto Thumbnail Bitmap con escalado personalizado. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Devuelve un objeto Thumbnail Bitmap con el tamaño especificado. |
| [getLayoutSlide()](#getLayoutSlide--) | Devuelve o establece la diapositiva de diseño para la diapositiva actual. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Devuelve o establece la diapositiva de diseño para la diapositiva actual. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Permite acceder a la diapositiva de notas, añadirla y eliminarla. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Devuelve todos los comentarios de diapositiva añadidos por un autor específico. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Guarda el contenido de la diapositiva como un archivo SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Guarda el contenido de la diapositiva como un archivo SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Guarda el contenido de la diapositiva como un archivo EMF. |
| [remove()](#remove--) | Elimina la diapositiva de la presentación. |
| [reset()](#reset--) | Restablece la posición, tamaño y formato de cada forma que tiene un prototipo en LayoutSlide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

Devuelve el administrador HeaderFooter de la diapositiva. Solo lectura [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Devuelve:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

Devuelve un número de diapositiva. El índice de la diapositiva en la colección [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) siempre es igual a SlideNumber - 1. Lectura/escritura int.

**Devuelve:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Devuelve un número de diapositiva. El índice de la diapositiva en la colección [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) siempre es igual a SlideNumber - 1. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Determina si la diapositiva especificada está oculta durante una presentación. Lectura/escritura boolean.

**Devuelve:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Determina si la diapositiva especificada está oculta durante una presentación. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Devuelve un objeto de imagen con escalado personalizado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scaleX | float | El valor por el cual escalar este Thumbnail en la dirección del eje x. |
| scaleY | float | El valor por el cual escalar este Thumbnail en la dirección del eje y. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Devuelve un objeto Thumbnail Image (20 % del tamaño real).

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage
### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```

Devuelve un objeto de imagen con el tamaño especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Tamaño de la imagen a crear. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

Devuelve un objeto Thumbnail tiff bitmap con los parámetros especificados.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Opciones Tiff. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Image object.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

Devuelve un objeto Thumbnail Bitmap.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones de renderizado. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Devuelve un objeto Thumbnail Bitmap con escalado personalizado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones de renderizado. |
| scaleX | float | El valor por el cual escalar este Thumbnail en la dirección del eje x. |
| scaleY | float | El valor por el cual escalar este Thumbnail en la dirección del eje y. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Devuelve un objeto Thumbnail Bitmap con el tamaño especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones de renderizado. |
| imageSize | java.awt.Dimension | Tamaño de la imagen a crear. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

Devuelve o establece la diapositiva de diseño para la diapositiva actual. Lectura/escritura [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

Devuelve o establece la diapositiva de diseño para la diapositiva actual. Lectura/escritura [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

Permite acceder a la diapositiva de notas, añadirla y eliminarla. Solo lectura [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Devuelve:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

Devuelve todos los comentarios de diapositiva añadidos por un autor específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autor de los comentarios a buscar o null para devolver todos los comentarios. |

**Devuelve:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Guarda el contenido de la diapositiva como un archivo SVG.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de destino |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Guarda el contenido de la diapositiva como un archivo SVG.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de destino |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opciones de generación SVG |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

Guarda el contenido de la diapositiva como un archivo EMF.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de destino |
### remove() {#remove--}
```
public abstract void remove()
```

Elimina la diapositiva de la presentación.
### reset() {#reset--}
```
public abstract void reset()
```

Restablece la posición, tamaño y formato de cada forma que tiene un prototipo en LayoutSlide.