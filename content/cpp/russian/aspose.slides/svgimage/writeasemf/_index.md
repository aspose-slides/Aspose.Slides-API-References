---
title: WriteAsEmf()
second_title: Справочник API Aspose.Slides для C++
description: Сохраняет изображение SVG как файл EMF.
type: docs
weight: 66
url: /ru/aspose.slides/svgimage/writeasemf/
---
## SvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) метод

Сохраняет изображение SVG как файл EMF.

```cpp
void Aspose::Slides::SvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Целевой поток |
## Примечания

В следующем примере демонстрируется, как сохранить изображение SVG в метафайл. 
```cpp
// Создает новое изображение SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Сохраняет изображение SVG как метафайл
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 Этот пример демонстрирует, как добавить изображение SVG в качестве метафайла в коллекцию изображений презентации. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Создает новое изображение SVG
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Сохраняет изображение SVG как метафайл
svgImage->WriteAsEmf(memStream);
// Добавляет метафайл в коллекцию изображений
pres->get_Images()->AddImage(memStream->ToArray());
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Stream](../../../system.io/stream/)
* Класс [SvgImage](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)