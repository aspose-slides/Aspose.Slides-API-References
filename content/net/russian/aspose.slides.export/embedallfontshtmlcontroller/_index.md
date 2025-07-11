---
title: EmbedAllFontsHtmlController
second_title: Aspose.Sildes для .NET API Справочник
description: Контроллер форматирования для использования при встраивании всех шрифтов презентации в формате WOFF.
type: docs
weight: 3590
url: /ru/aspose.slides.export/embedallfontshtmlcontroller/
---

## Класс EmbedAllFontsHtmlController

Контроллер форматирования для использования при встраивании всех шрифтов презентации в формате WOFF.

```csharp
public class EmbedAllFontsHtmlController : IHtmlFormattingController
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmbedAllFontsHtmlController](embedallfontshtmlcontroller#constructor)() | Создает новый экземпляр |
| [EmbedAllFontsHtmlController](embedallfontshtmlcontroller#constructor_1)(string[]) | Создает новый экземпляр |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [WriteAllFonts](../../aspose.slides.export/embedallfontshtmlcontroller/writeallfonts)(IHtmlGenerator, IPresentation) | Записывает все шрифты, содержащиеся в [`Presentation`](../../aspose.slides/presentation). |
| virtual [WriteDocumentEnd](../../aspose.slides.export/embedallfontshtmlcontroller/writedocumentend)(IHtmlGenerator, IPresentation) | Вызывается для записи нижнего колонтитула html-документа. Вызывается один раз при конвертации презентации. |
| virtual [WriteDocumentStart](../../aspose.slides.export/embedallfontshtmlcontroller/writedocumentstart)(IHtmlGenerator, IPresentation) | Вызывается для записи верхнего колонтитула html-документа. Вызывается один раз при конвертации презентации. |
| virtual [WriteFont](../../aspose.slides.export/embedallfontshtmlcontroller/writefont)(IHtmlGenerator, IFontData, IFontData, string, string, byte[]) | Записывает данные в формате base64 непосредственно в html-документ |
| virtual [WriteShapeEnd](../../aspose.slides.export/embedallfontshtmlcontroller/writeshapeend)(IHtmlGenerator, IShape) | Вызывается перед рендерингом фигуры. Вызывается один раз для каждой фигуры. Если эта функция что-либо записывает в генератор, генерация изображения текущего слайда будет завершена, добавленный фрагмент html будет вставлен, и новое изображение начнется над предыдущим. |
| virtual [WriteShapeStart](../../aspose.slides.export/embedallfontshtmlcontroller/writeshapestart)(IHtmlGenerator, IShape) | Вызывается перед рендерингом фигуры. Вызывается один раз для каждой фигуры. Если эта функция что-либо записывает в генератор, генерация изображения текущего слайда будет завершена, добавленный фрагмент html будет вставлен, и новое изображение начнется над предыдущим. |
| virtual [WriteSlideEnd](../../aspose.slides.export/embedallfontshtmlcontroller/writeslideend)(IHtmlGenerator, ISlide) | Вызывается для записи нижнего колонтитула html-слайда. Вызывается один раз для каждого слайда. |
| virtual [WriteSlideStart](../../aspose.slides.export/embedallfontshtmlcontroller/writeslidestart)(IHtmlGenerator, ISlide) | Вызывается для записи верхнего колонтитула html-слайда. Вызывается один раз для каждого слайда. |

### Смотрите также

* интерфейс [IHtmlFormattingController](../ihtmlformattingcontroller)
* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->