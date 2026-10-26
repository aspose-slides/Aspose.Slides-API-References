---
title: Convert
second_title: Справка API Aspose.Slides для C++
description: Представляет группу методов, предназначенных для конвертации Presentation.
type: docs
weight: 27
url: /ru/aspose.slides.lowcode/convert/
---
## Класс Convert


Represents a group of methods intended to convert [Presentation](../../aspose.slides/presentation/).

```cpp
class Convert
```

## Методы

| Method | Description |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | Конвертирует [Presentation](../../aspose.slides/presentation/) с использованием переданного расширения пути вывода для определения требуемого формата экспорта. |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Конвертирует входную презентацию в набор изображений формата JPEG. 

 Если имя выходного файла указано как "myPath/myFilename.jpeg", результат будет сохранён как набор файлов "myPath/myFilename_N.jpeg", где N — номер слайда. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Конвертирует входную презентацию в набор изображений формата JPEG. 

 Если имя выходного файла указано как "myPath/myFilename.jpeg", результат будет сохранён как набор файлов "myPath/myFilename_N.jpeg", где N — номер слайда. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Конвертирует входную презентацию в набор изображений формата JPEG. 

 Если имя выходного файла указано как "myPath/myFilename.jpeg", результат будет сохранён как набор файлов "myPath/myFilename_N.jpeg", где N — номер слайда. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | Конвертирует [Presentation](../../aspose.slides/presentation/) в PDF. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Конвертирует [Presentation](../../aspose.slides/presentation/) в PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Конвертирует [Presentation](../../aspose.slides/presentation/) в PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Конвертирует [Presentation](../../aspose.slides/presentation/) в PDF. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Конвертирует входную презентацию в набор изображений формата PNG. 

 Если имя выходного файла указано как "myPath/myFilename.png", результат будет сохранён как набор файлов "myPath/myFilename_N.png", где N — номер слайда. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Конвертирует входную презентацию в набор изображений формата PNG. 

 Если имя выходного файла указано как "myPath/myFilename.png", результат будет сохранён как набор файлов "myPath/myFilename_N.png", где N — номер слайда. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Конвертирует входную презентацию в набор изображений формата PNG. 

 Если имя выходного файла указано как "myPath/myFilename.png", результат будет сохранён как набор файлов "myPath/myFilename_N.png", где N — номер слайда. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | Конвертирует [Presentation](../../aspose.slides/presentation/) в SVG. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | Конвертирует [Presentation](../../aspose.slides/presentation/) в SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | Конвертирует [Presentation](../../aspose.slides/presentation/) в SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Конвертирует [Presentation](../../aspose.slides/presentation/) в SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Конвертирует [Presentation](../../aspose.slides/presentation/) в SVG. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Конвертирует входную презентацию в набор изображений формата TIFF. 

 Если имя выходного файла указано как "myPath/myFilename.tiff", результат будет сохранён как набор файлов "myPath/myFilename_N.tiff", где N — номер слайда. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | Конвертирует входную презентацию в формат TIFF с пользовательскими параметрами. Если имя выходного файла указано как "myPath/myFilename.tiff" и *multipage* **false**, результат будет сохранён как набор файлов "myPath/myFilename_N.tiff", где N — номер слайда. В противном случае, если *multipage* **true**, результат будет многостраничным документом "myPath/myFilename.tiff". |
## Типы

| Typedef | Description |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | Обратный вызов, который будет вызван для каждого [Slide](../../aspose.slides/slide/), ожидается возврат пути вывода. |
## Примечания



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## См. также

* Пространство имён [Aspose::Slides::LowCode](../)
* Библиотека [Aspose.Slides](../../)