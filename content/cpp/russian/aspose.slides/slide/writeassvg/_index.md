---
title: WriteAsSvg()
second_title: Aspose.Slides для C++ Справочник API
description: Сохраняет содержимое слайда в файл SVG.
type: docs
weight: 157
url: /ru/aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) метод


Saves the slide content as an SVG file.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Целевой поток |
## Примечания



The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

// Сохраняет первый слайд в файл SVG
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) метод


Saves the slide content as an SVG file.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Целевой поток |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | Параметры генерации SVG |
## Примечания



The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

auto options = System::MakeObject<SVGOptions>();
options->set_VectorizeText(true);

// Сохраняет первый слайд в файл SVG
pres->get_Slide(0)->WriteAsSvg(fileStream, options);
```

## См. также

* typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Stream](../../../system.io/stream/)
* Класс [Slide](../)
* Класс [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)