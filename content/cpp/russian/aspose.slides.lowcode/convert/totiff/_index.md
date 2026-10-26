---
title: ToTiff()
second_title: Справочник API Aspose.Slides for C++
description: Преобразует входную презентацию в набор изображений формата TIFF. Если имя выходного файла указано как \"myPath/myFilename.tiff\", результат будет сохранён как набор файлов \"myPath/myFilename_N.tiff\", где N — номер слайда.
type: docs
weight: 66
url: /ru/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) метод


Преобразует входную презентацию в набор изображений формата TIFF. 

 Если имя выходного файла задано как \"myPath/myFilename.tiff\", результат будет сохранён как набор файлов \"myPath/myFilename_N.tiff\", где N — номер слайда.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Входная презентация. |
| outputFileName | [System::String](../../../system/string/) | Имя выходного файла. |
## Примечания




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) метод


Преобразует входную презентацию в формат TIFF с пользовательскими параметрами. Если имя выходного файла задано как \"myPath/myFilename.tiff\" и *multipage*  равно **false**, результат будет сохранён как набор файлов \"myPath/myFilename_N.tiff\", где N — номер слайда. В противном случае, если *multipage*  равно **true**, результат будет многостраничным документом \"myPath/myFilename.tiff\".

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Входная презентация. |
| outputFileName | [System::String](../../../system/string/) | Имя выходного файла. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Параметры сохранения TIFF. |
| multipage | **bool** | Указывает, должен ли сгенерированный документ TIFF быть многостраничным. |
## Примечания




```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Presentation](../../../aspose.slides/presentation/)
* Класс [String](../../../system/string/)
* Класс [Convert](../)
* Класс [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Пространство имён [Aspose::Slides::LowCode](../../)
* Библиотека [Aspose.Slides](../../../)