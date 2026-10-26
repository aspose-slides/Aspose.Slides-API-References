---
title: IHtmlFormattingController
second_title: Aspose.Slides для Android через справочник Java API
description: Управляет генерацией html-файла.
type: docs
url: /ru/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

Управляет генерацией html-файла.
## Методы

| Метод | Описание |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Вызывается для записи заголовка html-документа. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Вызывается для записи нижнего колонтитула html-документа. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Вызывается для записи заголовка html-слайда. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Вызывается для записи нижнего колонтитула html-слайда. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Вызывается перед рендерингом фигуры. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Вызывается перед рендерингом фигуры. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Вызывается для записи заголовка html-документа. Вызывается один раз при конвертации презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Презентация, которая в данный момент отображается. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Вызывается для записи нижнего колонтитула html-документа. Вызывается один раз при конвертации презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Презентация, которая в данный момент отображается. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Вызывается для записи заголовка html-слайда. Вызывается один раз для каждого слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд, который в данный момент отображается. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Вызывается для записи нижнего колонтитула html-слайда. Вызывается один раз для каждого слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд, который в данный момент отображается. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Вызывается перед рендерингом фигуры. Вызывается один раз для каждой фигуры. Если эта функция что-либо записывает в генератор, текущая генерация изображения слайда будет завершена, добавленный html-фрагмент будет вставлен, и новое изображение начнётся поверх предыдущего.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| shape | [IShape](../../com.aspose.slides/ishape) | Фигура, которая будет отрисована. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Вызывается перед рендерингом фигуры. Вызывается один раз для каждой фигуры. Если эта функция что-либо записывает в генератор, текущая генерация изображения слайда будет завершена, добавленный html-фрагмент будет вставлен, и новое изображение начнётся поверх предыдущего.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| shape | [IShape](../../com.aspose.slides/ishape) | Фигура, отрисованная последней. |