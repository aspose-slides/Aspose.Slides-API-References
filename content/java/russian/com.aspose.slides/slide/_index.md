---
title: Slide
second_title: Aspose.Slides для Java API Reference
description: Представляет слайд в презентации.
type: docs
url: /ru/com.aspose.slides/slide/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Все реализованные интерфейсы:**
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)
```
public final class Slide extends BaseSlide implements ISlide
```

Представляет слайд в презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter слайда. |
| [getThemeManager()](#getThemeManager--) | Возвращает переопределяющий менеджер темы. |
| [getSlideNumber()](#getSlideNumber--) | Возвращает номер слайда. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Возвращает номер слайда. |
| [getHidden()](#getHidden--) | Определяет, скрыт ли указанный слайд во время показа. |
| [setHidden(boolean value)](#setHidden-boolean-) | Определяет, скрыт ли указанный слайд во время показа. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Указывает, должны ли фигуры на мастер-слайде отображаться на слайдах. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Указывает, должны ли фигуры на мастер-слайде отображаться на слайдах. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Возвращает объект Thumbnail Image с пользовательским масштабированием. |
| [getImage()](#getImage--) | Возвращает объект Thumbnail Image (20% от реального размера). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Возвращает объект Thumbnail Image с указанным размером. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Возвращает объект Thumbnail tiff image с указанными параметрами. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Возвращает объект Thumbnail Image. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Возвращает объект Thumbnail Image с пользовательским масштабированием. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Возвращает объект Thumbnail Image с указанным размером. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Сохраняет содержимое слайда в файл SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Сохраняет содержимое слайда в файл SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Сохраняет содержимое слайда в файл EMF. |
| [remove()](#remove--) | Удаляет слайд из презентации. |
| [getLayoutSlide()](#getLayoutSlide--) | Возвращает или задает макетный слайд для текущего слайда. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Возвращает или задает макетный слайд для текущего слайда. |
| [reset()](#reset--) | Сбрасывает положение, размер и форматирование каждой фигуры, имеющей прототип на LayoutSlide. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Позволяет получить доступ к слайду заметок, добавить и удалить его. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Возвращает все комментарии к слайду, добавленные определённым автором. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Объединяет участки с одинаковым форматированием во всех абзацах всех приемлемых фигур. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

Возвращает менеджер HeaderFooter слайда. Только для чтения [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Возвращаемое значение:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Возвращает переопределяющий менеджер темы. Только для чтения [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Возвращаемое значение:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

Возвращает номер слайда. Индекс слайда в коллекции [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) всегда равен SlideNumber - Presentation.FirstSlideNumber. Чтение/запись int.

**Возвращаемое значение:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

Возвращает номер слайда. Индекс слайда в коллекции [Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) всегда равен SlideNumber - Presentation.FirstSlideNumber. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

Определяет, скрыт ли указанный слайд во время показа. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

Определяет, скрыт ли указанный слайд во время показа. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Указывает, должны ли фигуры на мастер-слайде отображаться на слайдах. Чтение/запись boolean.

**Возвращаемое значение:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Указывает, должны ли фигуры на мастер-слайде отображаться на слайдах. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Возвращает объект Thumbnail Image с пользовательским масштабированием.

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // Access the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Create a full scale image
>      IImage bmp = sld.getImage(1f, 1f);
>      // Save the image to disk in JPEG format
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Converts the first slide in the presentation to a Bitmap object
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Saves the image in the PNG format
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
>          // Create a full scale image
>          IImage bmp = sld.getImage(1f, 1f);
>          // Save the image to disk in JPEG format
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
>      // Define dimensions
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Get scaled values of X and Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Create a full scale image
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Save the image to disk in JPEG format
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scaleX | float | Значение, на которое масштабировать этот Thumbnail по оси x. |
| scaleY | float | Значение, на которое масштабировать этот Thumbnail по оси y. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - объект IImage.

### getImage() {#getImage--}
```
public final IImage getImage()
```

Возвращает объект Thumbnail Image (20% от реального размера).

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage)

### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```

Возвращает объект Thumbnail Image с указанным размером.

--------------------

> ```
> Следующий пример показывает, как преобразовать слайды в изображения с пользовательскими размерами, используя C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Преобразует первый слайд презентации в объект Bitmap с указанным размером
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // Сохраняет изображение в формате JPEG
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Размер создаваемого изображения. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - объект Image.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

Возвращает объект Thumbnail tiff image с указанными параметрами.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Параметры Tiff. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - объект Image.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Возвращает объект Thumbnail Image.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - объект Image.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Возвращает объект Thumbnail Image с пользовательским масштабированием.

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Создать параметры рендеринга
>      IRenderingOptions options = new RenderingOptions();
>      // Создать параметры разметки заметок и комментариев
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Устанавливает позицию заметок на странице
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Устанавливает позицию комментариев на странице
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Устанавливает ширину области вывода комментариев
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Устанавливает цвет области комментариев
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Установить параметры разметки для рендеринга
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Преобразует первый слайд презентации в объект BufferedImage
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Сохраняет изображение в формате GIF
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |
| scaleX | float | Значение, на которое масштабировать этот Thumbnail по оси x. |
| scaleY | float | Значение, на которое масштабировать этот Thumbnail по оси y. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - объекты Bitmap.

### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Возвращает объект Thumbnail Image с указанным размером.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |
| imageSize | java.awt.Dimension | Размер создаваемого изображения. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - объект Image.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

Сохраняет содержимое слайда в файл SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // Сохраняет первый слайд как файл SVG
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Целевой поток |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Сохраняет содержимое слайда в файл SVG.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // Сохраняет первый слайд как файл SVG
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Целевой поток |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Параметры генерации SVG |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

Сохраняет содержимое слайда в файл EMF.

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // Сохраняет первый слайд как метафайл
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Целевой поток |

### remove() {#remove--}
```
public final void remove()
```

Удаляет слайд из презентации.

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

Возвращает или задает макетный слайд для текущего слайда. Чтение/запись [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

Возвращает или задает макетный слайд для текущего слайда. Чтение/запись [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```

Сбрасывает положение, размер и форматирование каждой фигуры, имеющей прототип на LayoutSlide.

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

Позволяет получить доступ к слайду заметок, добавить и удалить его. Только для чтения [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Возвращаемое значение:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

Возвращает все комментарии к слайду, добавленные определённым автором.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Автор комментариев для поиска или null для возврата всех комментариев. |

**Возвращаемое значение:**
com.aspose.slides.IComment[] - Массив [Comment](../../com.aspose.slides/comment).

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Объединяет участки с одинаковым форматированием во всех абзацах всех приемлемых фигур.