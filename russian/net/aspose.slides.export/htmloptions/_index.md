---
title: HtmlOptions
second_title: Справочник по API Aspose.Slides для .NET
description: Представляет параметры экспорта HTML.
type: docs
weight: 3570
url: /ru/net/aspose.slides.export/htmloptions/
---
## HtmlOptions class

Представляет параметры экспорта HTML.

```csharp
public class HtmlOptions : SaveOptions, IHtmlOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [HtmlOptions](htmloptions#constructor)() | Создает новый объект HtmlOptions для сохранения в один файл HTML. |
| [HtmlOptions](htmloptions#constructor_1)(ILinkEmbedController) | Создает новый объект HtmlOptions, определяющий обратный вызов. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Возвращает или устанавливает шрифт, используемый в случае, если исходный шрифт не найден. Чтение-записьString. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/htmloptions/deletepicturescroppedareas) { get; set; } | Логический флаг указывает, остаются ли обрезанные части частью документа. Если true, обрезанные части будут удалены, если false, они будут сериализованы в документе (что может привести к увеличению файла ) |
| [HtmlFormatter](../../aspose.slides.export/htmloptions/htmlformatter) { get; set; } | Возвращает или устанавливает шаблон HTML. Чтение/запись[`IHtmlFormatter`](../ihtmlformatter). |
| [JpegQuality](../../aspose.slides.export/htmloptions/jpegquality) { get; set; } | Возвращает или задает значение, определяющее качество изображений JPEG внутри документа PDF. Чтение/записьByte. |
| [NotesCommentsLayouting](../../aspose.slides.export/htmloptions/notescommentslayouting) { get; } | Предоставляет параметры, управляющие размещением примечаний и комментариев в экспортируемом документе. |
| [PicturesCompression](../../aspose.slides.export/htmloptions/picturescompression) { get; set; } | Представляет уровень сжатия изображений |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Представляет объект обратного вызова для сохранения обновлений хода выполнения в процентах. См.[`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShowHiddenSlides](../../aspose.slides.export/htmloptions/showhiddenslides) { get; set; } | Указывает, должен ли сгенерированный документ включать скрытые слайды или нет. По умолчанию:` false` . |
| [SlideImageFormat](../../aspose.slides.export/htmloptions/slideimageformat) { get; set; } | Возвращает или задает параметры формата изображения слайда. Чтение/запись[`ISlideImageFormat`](../islideimageformat). |
| [SvgResponsiveLayout](../../aspose.slides.export/htmloptions/svgresponsivelayout) { get; set; } | True, чтобы исключить атрибуты ширины и высоты из контейнера svg — это сделает макет отзывчивым. Ложь - иначе. Чтение/записьBoolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Возвращает наборы объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или будет прерван. Чтение/запись[`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Смотрите также

* class [SaveOptions](../saveoptions)
* interface [IHtmlOptions](../ihtmloptions)
* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->