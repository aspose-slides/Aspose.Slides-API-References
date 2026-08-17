---
title: IHtmlFormattingController
second_title: Aspose.Slides for Java API Reference
description: Управляет генерацией html файла.
type: docs
url: /ru/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

Управляет генерацией html файла.
## Методы

| Метод | Описание |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Вызывается для записи заголовка html документа. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Вызывается для записи подвала html документа. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Вызывается для записи заголовка html слайда. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Вызывается для записи подвала html слайда. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Вызывается перед отрисовкой фигуры. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Вызывается перед отрисовкой фигуры. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Вызывается для записи заголовка html документа. Вызывается один раз за конвертацию презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Презентация, в данный момент рендерится. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Вызывается для записи подвала html документа. Вызывается один раз за конвертацию презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Презентация, в данный момент рендерится. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Вызывается для записи заголовка html слайда. Вызывается один раз для каждого слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд, в данный момент рендерится. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Вызывается для записи подвала html слайда. Вызывается один раз для каждого слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд, в данный момент рендерится. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Вызывается перед отрисовкой фигуры. Вызывается один раз для каждой фигуры. Если эта функция записывает что-либо в generator, генерация текущего изображения слайда будет завершена, добавленный html-фрагмент вставлен, и новое изображение будет начато поверх предыдущего.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| shape | [IShape](../../com.aspose.slides/ishape) | Фигура, которая собирается отрисоваться. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Вызывается перед отрисовкой фигуры. Вызывается один раз для каждой фигуры. Если эта функция записывает что-либо в generator, генерация текущего изображения слайда будет завершена, добавленный html-фрагмент вставлен, и новое изображение будет начато поверх предыдущего.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| shape | [IShape](../../com.aspose.slides/ishape) | Фигура, которая отрисована последней. |