---
title: EmbedAllFontsHtmlController
second_title: Справочник API Aspose.Slides для Java
description: Класс контроллера форматирования, используемый для встраивания всех шрифтов презентации в формате WOFF.
type: docs
url: /ru/com.aspose.slides/embedallfontshtmlcontroller/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

Класс контроллера форматирования, используемый для встраивания всех шрифтов презентации в формате WOFF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Создаёт новый экземпляр |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Создаёт новый экземпляр |
## Методы

| Метод | Описание |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Вызывается для записи заголовка html-документа. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Вызывается для записи нижнего колонтитула html-документа. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Вызывается для записи заголовка html-слайда. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Вызывается для записи нижнего колонтитула html-слайда. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Вызывается перед отрисовкой фигуры. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Вызывается перед отрисовкой фигуры. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Записывает все шрифты, содержащиеся в [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Записывает данные в виде base64 непосредственно в HTML-документ |
### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```

Создаёт новый экземпляр

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```

Создаёт новый экземпляр

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Шрифты, которые должны быть исключены из встраивания |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Вызывается для записи заголовка html-документа. Вызывается один раз за конвертацию презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Презентация, которая в данный момент отображается. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Вызывается для записи нижнего колонтитула html-документа. Вызывается один раз за конвертацию презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Презентация, которая в данный момент отображается. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Вызывается для записи заголовка html-слайда. Вызывается один раз для каждого слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд, который в данный момент отображается. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Вызывается для записи нижнего колонтитула html-слайда. Вызывается один раз для каждого слайда.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд, который в данный момент отображается. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Вызывается перед отрисовкой фигуры. Вызывается один раз для каждой фигуры. Если эта функция записывает что-либо в generator, генерация текущего изображения слайда будет завершена, добавленный html-фрагмент будет вставлен, и новое изображение начнётся поверх предыдущего.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| shape | [IShape](../../com.aspose.slides/ishape) | Фигура, которая собирается быть отрисована. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Вызывается перед отрисовкой фигуры. Вызывается один раз для каждой фигуры. Если эта функция записывает что-либо в generator, генерация текущего изображения слайда будет завершена, добавленный html-фрагмент будет вставлен, и новое изображение начнётся поверх предыдущего.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| shape | [IShape](../../com.aspose.slides/ishape) | Фигура, которая отрисована последней. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

Записывает все шрифты, содержащиеся в [Presentation](../../com.aspose.slides/presentation).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Объект вывода. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Презентация, которая в данный момент отображается. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

Записывает данные в виде base64 непосредственно в HTML-документ

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | HTML-генератор |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Шрифт для сериализации |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Заменённый шрифт (если произошла замена шрифта), иначе null |
| fontStyle | java.lang.String | Стиль шрифта |
| fontWeight | java.lang.String | Насыщенность шрифта |
| fontData | byte[] | Данные шрифта |