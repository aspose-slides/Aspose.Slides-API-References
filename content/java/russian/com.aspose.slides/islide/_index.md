---
title: ISlide
second_title: Справочник API Aspose.Slides для Java
description: Представляет слайд в презентации.
type: docs
url: /ru/com.aspose.slides/islide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Represents a slide in a presentation.
## Методы

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter слайда. |
| [getSlideNumber()](#getSlideNumber--) | Возвращает номер слайда. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Возвращает номер слайда. |
| [getHidden()](#getHidden--) | Определяет, скрыт ли указанный слайд во время показа. |
| [setHidden(boolean value)](#setHidden-boolean-) | Определяет, скрыт ли указанный слайд во время показа. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Возвращает объект изображения с пользовательским масштабированием. |
| [getImage()](#getImage--) | Возвращает объект миниатюры Image (20% реального размера). |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | Возвращает объект изображения с указанным размером. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Возвращает объект миниатюры tiff bitmap с указанными параметрами. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Возвращает объект миниатюры Bitmap. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Возвращает объект миниатюры Bitmap с пользовательским масштабированием. |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Возвращает объект миниатюры Bitmap с указанным размером. |
| [getLayoutSlide()](#getLayoutSlide--) | Возвращает или задает макет слайда для текущего слайда. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Возвращает или задает макет слайда для текущего слайда. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Позволяет получить доступ к слайду заметок, добавить и удалить его. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Возвращает все комментарии слайда, добавленные определённым автором. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Сохраняет содержимое слайда в файл SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Сохраняет содержимое слайда в файл SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Сохраняет содержимое слайда в файл EMF. |
| [remove()](#remove--) | Удаляет слайд из презентации. |
| [reset()](#reset--) | Сбрасывает положение, размер и форматирование каждой фигуры, имеющей прототип на LayoutSlide. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

Возвращает менеджер HeaderFooter слайда. Только для чтения [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Возвращает:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

Возвращает номер слайда. Индекс слайда в коллекции [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) всегда равен SlideNumber - 1. Чтение/запись int.

**Возвращает:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

Возвращает номер слайда. Индекс слайда в коллекции [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) всегда равен SlideNumber - 1. Чтение/запись int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

Определяет, скрыт ли указанный слайд во время показа. Чтение/запись boolean.

**Возвращает:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

Определяет, скрыт ли указанный слайд во время показа. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

Возвращает объект изображения с пользовательским масштабированием.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| scaleX | float | Значение, на которое масштабировать миниатюру по оси X. |
| scaleY | float | Значение, на которое масштабировать миниатюру по оси Y. |

**Возвращает:**
[IImage](../../com.aspose.slides/iimage) - Объект Image java.awt.image.BufferedImage

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

Возвращает объект миниатюры Image (20% реального размера).

**Возвращает:**
[IImage](../../com.aspose.slides/iimage) - Объект Image java.awt.image.BufferedImage

### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```

Возвращает объект изображения с указанным размером.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageSize | java.awt.Dimension | Размер создаваемого изображения. |

**Возвращает:**
[IImage](../../com.aspose.slides/iimage) - Объект Bitmap.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

Возвращает объект миниатюры tiff bitmap с указанными параметрами.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Параметры Tiff. |

**Возвращает:**
[IImage](../../com.aspose.slides/iimage) - Объект Image.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

Возвращает объект миниатюры Bitmap.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |

**Возвращает:**
[IImage](../../com.aspose.slides/iimage) - Объекты Bitmap.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

Возвращает объект миниатюры Bitmap с пользовательским масштабированием.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |
| scaleX | float | Значение, на которое масштабировать миниатюру по оси X. |
| scaleY | float | Значение, на которое масштабировать миниатюру по оси Y. |

**Возвращает:**
[IImage](../../com.aspose.slides/iimage) - Объекты Bitmap.

### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```

Возвращает объект миниатюры Bitmap с указанным размером.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |
| imageSize | java.awt.Dimension | Размер создаваемого изображения. |

**Возвращает:**
[IImage](../../com.aspose.slides/iimage) - Объекты Bitmap.

### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

Возвращает или задает макет слайда для текущего слайда. Чтение/запись [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Возвращает:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

Возвращает или задает макет слайда для текущего слайда. Чтение/запись [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

Позволяет получить доступ к слайду заметок, добавить и удалить его. Только для чтения [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Возвращает:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

Возвращает все комментарии слайда, добавленные определённым автором.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Автор комментариев для поиска или null для возврата всех комментариев. |

**Возвращает:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

Сохраняет содержимое слайда в файл SVG.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Целевой поток |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

Сохраняет содержимое слайда в файл SVG.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Целевой поток |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Опции генерации SVG |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

Сохраняет содержимое слайда в файл EMF.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Целевой поток |

### remove() {#remove--}
```
public abstract void remove()
```

Удаляет слайд из презентации.

### reset() {#reset--}
```
public abstract void reset()
```

Сбрасывает положение, размер и форматирование каждой фигуры, имеющей прототип на LayoutSlide.