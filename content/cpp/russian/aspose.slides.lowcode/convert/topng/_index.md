---
title: ToPng()
second_title: Aspose.Slides для C++ API Reference
description: Преобразует входную презентацию в набор изображений формата PNG. Если имя выходного файла указано как \"myPath/myFilename.png\", результат будет сохранён в виде набора файлов \"myPath/myFilename_N.png\", где N — номер слайда.
type: docs
weight: 53
url: /ru/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) method


Преобразует входную презентацию в набор изображений формата PNG. 

 Если имя выходного файла указано как \"myPath/myFilename.png\", результат будет сохранён в виде набора файлов \"myPath/myFilename_N.png\", где N — номер слайда.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Входная презентация. |
| outputFileName | [System::String](../../../system/string/) | Имя выходного файла. |
## Примечания




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) method


Преобразует входную презентацию в набор изображений формата PNG. 

 Если имя выходного файла указано как \"myPath/myFilename.png\", результат будет сохранён в виде набора файлов \"myPath/myFilename_N.png\", где N — номер слайда.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Входная презентация |
| outputFileName | [System::String](../../../system/string/) | Имя выходного файла. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Размер каждого генерируемого изображения. |
## Примечания




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) method


Преобразует входную презентацию в набор изображений формата PNG. 

 Если имя выходного файла указано как \"myPath/myFilename.png\", результат будет сохранён в виде набора файлов \"myPath/myFilename_N.png\", где N — номер слайда.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Входная презентация. |
| outputFileName | [System::String](../../../system/string/) | Имя выходного файла. |
| scale | **float** | Коэффициент масштабирования, применяемый к выходным изображениям относительно исходного размера слайда. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Параметры рендеринга. |
## Примечания 




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [Size](../../../system.drawing/size/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)