---
title: Slide
second_title: Referencia de API de Aspose.Slides para Android vía Java
description: Representa una diapositiva en una presentación.
type: docs
url: /es/com.aspose.slides/slide/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Todas las Interfaces Implementadas:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Representa una diapositiva en una presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Devuelve el administrador HeaderFooter de la diapositiva. |
| [getThemeManager()](#getThemeManager--) | Devuelve el administrador de tema sobrescrito. |
| [getSlideNumber()](#getSlideNumber--) | Devuelve un número de diapositiva. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Devuelve un número de diapositiva. |
| [getHidden()](#getHidden--) | Determina si la diapositiva especificada está oculta durante la presentación. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determina si la diapositiva especificada está oculta durante la presentación. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Devuelve un objeto Thumbnail Image con escalado personalizado. |
| [getImage()](#getImage--) | Devuelve un objeto Thumbnail Image (20% del tamaño real). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Devuelve un objeto Thumbnail Image con tamaño especificado. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Devuelve un objeto de imagen tiff Thumbnail con parámetros especificados. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Devuelve un objeto Thumbnail Image. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Devuelve un objeto Thumbnail Image con escalado personalizado. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Devuelve un objeto Thumbnail Image con tamaño especificado. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Guarda el contenido de la diapositiva como un archivo SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Guarda el contenido de la diapositiva como un archivo SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Guarda el contenido de la diapositiva como un archivo EMF. |
| [remove()](#remove--) | Elimina la diapositiva de la presentación. |
| [getLayoutSlide()](#getLayoutSlide--) | Devuelve o establece la diapositiva de diseño para la diapositiva actual. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Devuelve o establece la diapositiva de diseño para la diapositiva actual. |
| [reset()](#reset--) | Restablece la posición, el tamaño y el formato de cada forma que tiene un prototipo en LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Permite acceder a la diapositiva de notas, agregarla y eliminarla. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Devuelve todos los comentarios de diapositiva añadidos por un autor específico. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Une ejecuciones con el mismo formato en todos los párrafos en todas las formas aceptables. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Devuelve el administrador HeaderFooter de la diapositiva. Solo lectura [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Devuelve:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Devuelve el administrador de tema sobrescrito. Solo lectura [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Devuelve:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Devuelve un número de diapositiva. El índice de la diapositiva en la colección [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) siempre es igual a SlideNumber - Presentation.FirstSlideNumber. Lectura/escritura int.

**Devuelve:**
int
### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Establece un número de diapositiva. El índice de la diapositiva en la colección [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) siempre es igual a SlideNumber - Presentation.FirstSlideNumber. Lectura/escritura int.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Determina si la diapositiva especificada está oculta durante la presentación. Lectura/escritura boolean.

**Devuelve:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Determina si la diapositiva especificada está oculta durante la presentación. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. Lectura/escritura boolean.

**Devuelve:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Especifica si las formas en la diapositiva maestra deben mostrarse en las diapositivas o no. Lectura/escritura boolean.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | boolean |  |
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Devuelve un objeto Thumbnail Image con escalado personalizado.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // Acceder a la primera diapositiva
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Crear una imagen a escala completa
>      IImage bmp = sld.getImage(1f, 1f);
>      // Guardar la imagen en disco en formato JPEG
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Convierte la primera diapositiva de la presentación a un objeto Bitmap
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Guarda la imagen en formato PNG
>      bmp.save("Slide_0.png", ImageFormat.Png);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.ppt");
>  try {
>      for (ISlide sld : pres.getSlides())
>      {
>          // Crear una imagen a escala completa
>          IImage bmp = sld.getImage(1f, 1f);
>          // Guardar la imagen en disco en formato JPEG
>          bmp.save("Slide_"+sld.getSlideNumber()+"0.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.pptx");
>  try {
>      // Definir dimensiones
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Obtener valores escalados de X e Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Crear una imagen a escala completa
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Guardar la imagen en disco en formato JPEG
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scaleX | float | El valor por el cual escalar este Thumbnail en la dirección del eje x. |
| scaleY | float | El valor por el cual escalar este Thumbnail en la dirección del eje y. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - objeto IImage.
### getImage() {#getImage--}
```
public final IImage getImage()
```

Devuelve un objeto Thumbnail Image (20% del tamaño real).

**Devuelve:**
[IImage](../../com.aspose.slides/iimage)
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public final IImage getImage(Size imageSize)
```

Devuelve un objeto Thumbnail Image con tamaño especificado.

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Convierte la primera diapositiva de la presentación a un Bitmap con el tamaño especificado
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // Guarda la imagen en formato JPEG
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Tamaño de la imagen a crear. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - objeto Image.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Devuelve un objeto de imagen tiff Thumbnail con parámetros especificados.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Opciones tiff. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - objeto Image.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Devuelve un objeto Thumbnail Image.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones de renderizado. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - objeto Image.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Devuelve un objeto Thumbnail Image con escalado personalizado.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Crear las opciones de renderizado
>      IRenderingOptions options = new RenderingOptions();
>      // Crear opciones de diseño de notas y comentarios
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Establece la posición de las notas en la página
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Establece la posición de los comentarios en la página
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Establece el ancho del área de salida de los comentarios
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Establece el color del área de comentarios
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Establecer opciones de diseño para el renderizado
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Convierte la primera diapositiva de la presentación a un objeto android.graphics.Bitmap
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Guarda la imagen en formato GIF
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones de renderizado. |
| scaleX | float | El valor por el cual escalar este Thumbnail en la dirección del eje x. |
| scaleY | float | El valor por el cual escalar este Thumbnail en la dirección del eje y. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - objetos Bitmap.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage getImage(IRenderingOptions options, Size imageSize)
```

Devuelve un objeto Thumbnail Image con tamaño especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opciones de renderizado. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Tamaño de la imagen a crear. |

**Devuelve:**
[IImage](../../com.aspose.slides/iimage) - objeto Image.
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Guarda el contenido de la diapositiva como un archivo SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Guarda la primera diapositiva como un archivo SVG
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de salida objetivo |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Guarda el contenido de la diapositiva como un archivo SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // Guarda la primera diapositiva como un archivo SVG
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de salida objetivo |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Opciones de generación SVG |
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Guarda el contenido de la diapositiva como un archivo EMF.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // Guarda la primera diapositiva como un metafile
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.OutputStream | Flujo de salida objetivo |
### remove() {#remove--}
```
public final void remove()
```

Elimina la diapositiva de la presentación.
### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

Devuelve o establece la diapositiva de diseño para la diapositiva actual. Lectura/escritura [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Devuelve:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Devuelve o establece la diapositiva de diseño para la diapositiva actual. Lectura/escritura [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |
### reset() {#reset--}
```
public final void reset()
```

Restablece la posición, el tamaño y el formato de cada forma que tiene un prototipo en LayoutSlide.
### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Permite acceder a la diapositiva de notas, agregarla y eliminarla. Solo lectura [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Devuelve:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Devuelve todos los comentarios de diapositiva añadidos por un autor específico.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Autor de los comentarios a buscar o null para devolver todos los comentarios. |

**Devuelve:**
com.aspose.slides.IComment[] - Array de [Comment](../../com.aspose.slides/comment).
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Une ejecuciones con el mismo formato en todos los párrafos en todas las formas aceptables.