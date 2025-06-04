---
title: SVGOptions
second_title: Aspose.Sildes для .NET API Reference
description: Представляет параметры SVG.
type: docs
weight: 4240
url: /ru/aspose.slides.export/svgoptions/
---

## SVGOptions class

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
| static [Default](../../aspose.slides.export/svgoptions/default) { get; } | Возвращает настройки по умолчанию. Только для чтения [`SVGOptions`](../svgoptions). |
| static [Simple](../../aspose.slides.export/svgoptions/simple) { get; } | Возвращает настройки для самой простой и маленькой генерации файла SVG. Только для чтения [`SVGOptions`](../svgoptions). |
| static [WYSIWYG](../../aspose.slides.export/svgoptions/wysiwyg) { get; } | Возвращает настройки для самой точной генерации файла SVG. Только для чтения [`SVGOptions`](../svgoptions). |
| [DefaultRegularFont](../../aspose.slides.export/saveoptions/defaultregularfont) { get; set; } | Возвращает или устанавливает шрифт, используемый в случае, если исходный шрифт не найден. Читаемое/записываемое значение String. |
| [DeletePicturesCroppedAreas](../../aspose.slides.export/svgoptions/deletepicturescroppedareas) { get; set; } | Логический флаг, указывающий, остаются ли обрезанные части частью документа. Если true, обрезанные части будут удалены, если false — они будут сериализованы в документе (что может привести к большему размеру файла). |
| [Disable3DText](../../aspose.slides.export/svgoptions/disable3dtext) { get; set; } | Определяет, отключен ли 3D текст в SVG. Читаемое/записываемое значение Boolean. |
| [DisableFontLigatures](../../aspose.slides.export/svgoptions/disablefontligatures) { get; set; } | Получает или устанавливает значение, указывающее, отображается ли текст без использования лигатур. Если установлено значение `true`, лигатуры будут отключены в выходных данных. По умолчанию это свойство установлено в `false`. |
| [DisableGradientSplit](../../aspose.slides.export/svgoptions/disablegradientsplit) { get; set; } | Отключает разделение градиентов FromCornerX и FromCenter. Читаемое/записываемое значение Boolean. |
| [DisableLineEndCropping](../../aspose.slides.export/svgoptions/disablelineendcropping) { get; set; } | SVG 1.1 не имеет возможности определения отступов для маркеров. Движок записи SVG Aspose.Slides имеет обход этого проблемы: он обрезает конец линии со стрелкой, чтобы линия не перекрывала маркеры. Этот параметр отключает такое поведение. Читаемое/записываемое значение Boolean. |
| [ExternalFontsHandling](../../aspose.slides.export/svgoptions/externalfontshandling) { get; set; } | Определяет способ обработки внешне загружаемых шрифтов. Читаемое/записываемое значение [`SvgExternalFontsHandling`](../svgexternalfontshandling). |
| [GradientStyle](../../aspose.slides.export/saveoptions/gradientstyle) { get; set; } | Возвращает или устанавливает визуальный стиль градиента. Читаемое/записываемое значение [`GradientStyle`](../../aspose.slides/gradientstyle). |
| [InkOptions](../../aspose.slides.export/svgoptions/inkoptions) { get; } | Предоставляет параметры, которые контролируют внешний вид объектов Ink в экспортированном документе. Только для чтения [`IInkOptions`](../iinkoptions) |
| [JpegQuality](../../aspose.slides.export/svgoptions/jpegquality) { get; set; } | Определяет качество кодирования JPEG. Читаемое/записываемое значение Int32. |
| [MetafileRasterizationDpi](../../aspose.slides.export/svgoptions/metafilerasterizationdpi) { get; set; } | Возвращает или устанавливает нижний предел разрешения для растеризации метафайлов. Читаемое/записываемое значение Int32. |
| [PicturesCompression](../../aspose.slides.export/svgoptions/picturescompression) { get; set; } | Представляет уровень сжатия изображений. |
| [ProgressCallback](../../aspose.slides.export/saveoptions/progresscallback) { get; set; } | Представляет объект обратного вызова для сохранения обновлений прогресса в процентах. См. [`IProgressCallback`](../../aspose.slides/iprogresscallback). |
| [ShapeFormattingController](../../aspose.slides.export/svgoptions/shapeformattingcontroller) { get; set; } | Возвращает и устанавливает интерфейс обратного вызова, который позволяет пользователю контролировать преобразование фигур. Читаемое/записываемое значение [`ISvgShapeFormattingController`](../isvgshapeformattingcontroller). |
| [SkipJavaScriptLinks](../../aspose.slides.export/saveoptions/skipjavascriptlinks) { get; set; } | Указывает, необходимо ли пропускать гиперссылки с вызовами JavaScript при сохранении презентации. Читаемое/записываемое значение Boolean. Значение по умолчанию — **false**. |
| [UseFrameRotation](../../aspose.slides.export/svgoptions/useframerotation) { get; set; } | Определяет, следует ли выполнять указанное вращение фигуры при рендеринге или нет. Читаемое/записываемое значение Boolean. Значение по умолчанию — true. |
| [UseFrameSize](../../aspose.slides.export/svgoptions/useframesize) { get; set; } | Определяет, будет ли текстовый фрейм включен в область рендеринга или нет. Читаемое/записываемое значение Boolean. Значение по умолчанию — false. |
| [VectorizeText](../../aspose.slides.export/svgoptions/vectorizetext) { get; set; } | Определяет, будет ли текст на слайде сохранен как графика. Читаемое/записываемое значение Boolean. |
| [WarningCallback](../../aspose.slides.export/saveoptions/warningcallback) { get; set; } | Возвращает или устанавливает объект, который получает предупреждения и решает, будет ли процесс загрузки продолжен или прерван. Читаемое/записываемое значение [`IWarningCallback`](../../aspose.slides.warnings/iwarningcallback). |

### Также см.

* класс [SaveOptions](../saveoptions)
* интерфейс [ISVGOptions](../isvgoptions)
* пространство имен [Aspose.Slides.Export](../../aspose.slides.export)
* сборка [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->