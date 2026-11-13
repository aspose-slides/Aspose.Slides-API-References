---
title: SVGOptions
second_title: Справочник API Aspose.Sildes для .NET
description: Представляет параметры SVG.
type: docs
weight: 4450
url: /ru/aspose.slides.export/svgoptions/
---
## SVGOptions класс

Представляет параметры SVG.

```csharp
public sealed class SVGOptions : SaveOptions, ISVGOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [SVGOptions](svgoptions#constructor)() | Инициализирует новый экземпляр класса SVGOptions. |
| [SVGOptions](svgoptions#constructor_1)(ILinkEmbedController) | Инициализирует новый экземпляр класса SVGOptions, указывая объект контроллера встраивания ссылок. |

## Свойства

| Имя | Описание |
| --- | --- |
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Возвращает настройки по умолчанию. Только для чтения [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Возвращает настройки для простейшей и минимального по размеру генерации SVG-файла. Только для чтения [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Возвращает настройки для наиболее точной генерации SVG-файла. Только для чтения [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Возвращает или задает шрифт, используемый в случае, если исходный шрифт не найден. Чтение/запись String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Логический флаг, указывающий, остаются ли обрезанные части частью документа. Если true, обрезанные части будут удалены; если false, они будут сериализованы в документе (что может привести к увеличению размера файла). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Определяет, отключён ли 3D-текст в SVG. Чтение/запись Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Получает или задает значение, указывающее, отображается ли текст без использования лигатур. При установке в `true` лигатуры будут отключены в выводе. По умолчанию свойство установлено в `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Отключает разбиение градиентов FromCornerX и FromCenter. Чтение/запись Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | В SVG 1.1 отсутствует возможность задавать отступы для маркеров. Движок записи SVG в Aspose.Slides имеет обходной путь: он обрезает конец линии со стрелкой, чтобы линия не перекрывала маркеры. Эта опция отключает такое поведение. Чтение/запись Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Определяет способ обработки внешне загруженных шрифтов. Чтение/запись [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Возвращает или задает визуальный стиль градиента. Чтение/запись [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Предоставляет параметры, управляющие внешним видом объектов Ink в экспортируемом документе. Только для чтения [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Определяет качество кодирования JPEG. Чтение/запись Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Возвращает или задает нижний предел разрешения для растрирования метафайла. Чтение/запись Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Представляет уровень сжатия изображений |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Представляет объект обратного вызова для сохранения обновлений прогресса в процентах. Смотрите [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Возвращает и задает интерфейс обратного вызова, позволяющий пользователю контролировать преобразование фигур. Чтение/запись [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Указывает, следует ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Чтение/запись Boolean. Значение по умолчанию **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Определяет, следует ли выполнять указанное вращение фигуры при рендеринге. Чтение/запись Boolean. Значение по умолчанию true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Определяет, будет ли текстовый кадр включён в область рендеринга. Чтение/запись Boolean. Значение по умолчанию false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Определяет, будет ли текст на слайде сохранён как графика. Чтение/запись Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Возвращает или задает объект, получающий предупреждения и решающий, продолжать ли процесс загрузки или прервать его. Чтение/запись [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Смотрите также

* класс [SaveOptions](../saveoptions)
* интерфейс [ISVGOptions](../isvgoptions)
* пространство имён [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->