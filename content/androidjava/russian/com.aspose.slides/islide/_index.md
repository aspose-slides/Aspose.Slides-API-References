---
title: ISlide
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет слайд в презентации.
type: docs
url: /ru/com.aspose.slides/islide/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

Представляет слайд в презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter слайда. |
| [getSlideNumber()](#getSlideNumber--) | Возвращает номер слайда. |
| [setSlideNumber(int value)](#setSlideNumber-int-) | Возвращает номер слайда. |
| [getHidden()](#getHidden--) | Определяет, скрыт ли указанный слайд во время показа слайдов. |
| [setHidden(boolean value)](#setHidden-boolean-) | Определяет, скрыт ли указанный слайд во время показа слайдов. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Возвращает объект изображения с пользовательским масштабированием. |
| [getImage()](#getImage--) | Возвращает объект Thumbnail Image (20 % от реального размера). |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | Возвращает объект изображения с указанным размером. |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | Возвращает объект Thumbnail tiff bitmap с указанными параметрами. |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Возвращает объект Thumbnail Bitmap. |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | Возвращает объект Thumbnail Bitmap с пользовательским масштабированием. |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Возвращает объект Thumbnail Bitmap с указанным размером. |
| [getLayoutSlide()](#getLayoutSlide--) | Возвращает или задает макетный слайд для текущего слайда. |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | Возвращает или задает макетный слайд для текущего слайда. |
| [getNotesSlideManager()](#getNotesSlideManager--) | Позволяет получить доступ к слайду заметок, добавить и удалить его. |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | Возвращает все комментарии к слайду, добавленные определённым автором. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Сохраняет содержимое слайда в файл SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Сохраняет содержимое слайда в файл SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | Сохраняет содержимое слайда в файл EMF. |
| [remove()](#remove--) | Удаляет слайд из презентации. |
| [reset()](#reset--) | Сбрасывает положение, размер и форматирование каждой формы, у которой есть прототип на LayoutSlide. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```


Возвращает менеджер HeaderFooter слайда. Только чтение [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**Возвращаемое значение:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)
### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```


Возвращает номер слайда. Индекс слайда в коллекции [IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) всегда равен SlideNumber - 1. Чтение/запись int.

**Возвращаемое значение:**
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


Определяет, скрыт ли указанный слайд во время показа слайдов. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```


Определяет, скрыт ли указанный слайд во время показа слайдов. Чтение/запись boolean.

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
| scaleX | float | Значение, на которое нужно масштабировать этот Thumbnail по оси x. |
| scaleY | float | Значение, на которое нужно масштабировать этот Thumbnail по оси y. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - объект Image android.graphics.Bitmap
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Возвращает объект Thumbnail Image (20 % от реального размера).

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - объект Image android.graphics.Bitmap
### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```


Возвращает объект изображения с указанным размером.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | Размер изображения для создания. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - объект Bitmap.
### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```


Возвращает объект Thumbnail tiff bitmap с указанными параметрами.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Параметры Tiff. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - объект Image.
### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```


Возвращает объект Thumbnail Bitmap.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - объекты Bitmap.
### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```


Возвращает объект Thumbnail Bitmap с пользовательским масштабированием.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |
| scaleX | float | Значение, на которое нужно масштабировать этот Thumbnail по оси x. |
| scaleY | float | Значение, на которое нужно масштабировать этот Thumbnail по оси y. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - объекты Bitmap.
### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```


Возвращает объект Thumbnail Bitmap с указанным размером.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Размер изображения для создания. |

**Возвращаемое значение:**
[IImage](../../com.aspose.slides/iimage) - объекты Bitmap.
### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```


Возвращает или задает макетный слайд для текущего слайда. Чтение/запись [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Возвращаемое значение:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```


Возвращает или задает макетный слайд для текущего слайда. Чтение/запись [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```


Позволяет получить доступ к слайду заметок, добавить и удалить его. Только чтение [INotesSlideManager](../../com.aspose.slides/inotesslidemanager).

**Возвращаемое значение:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)
### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```


Возвращает все комментарии к слайду, добавленные определённым автором.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | Автор комментариев для поиска или null для возврата всех комментариев. |

**Возвращаемое значение:**
com.aspose.slides.IComment[] - массив [IComment](../../com.aspose.slides/icomment).
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
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | Параметры генерации SVG |

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


Сбрасывает положение, размер и форматирование каждой формы, у которой есть прототип на LayoutSlide.