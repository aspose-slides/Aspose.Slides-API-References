---
title: WriteAsEmf()
second_title: Aspose.Slides для C++ справочник API
description: Сохраняет SVG-изображение в файл EMF.
type: docs
weight: 53
url: /ru/aspose.slides/isvgimage/writeasemf/
---
## ISvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) метод

Сохраняет SVG-изображение в файл EMF.

```cpp
virtual void Aspose::Slides::ISvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Целевой поток |

## Remarks

Следующий пример демонстрирует, как сохранить SVG-изображение в метафайл. 
```cpp
// Создает новое SVG изображение
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// Сохраняет SVG изображение в метафайл
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
Этот пример демонстрирует, как добавить SVG-изображение в качестве метафайла в коллекцию изображений презентации. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// Создает новое SVG изображение
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// Сохраняет SVG изображение как метафайл
svgImage->WriteAsEmf(memStream);
// Добавляет метафайл в коллекцию изображений
pres->get_Images()->AddImage(memStream->ToArray());
```

## See Also

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [Stream](../../../system.io/stream/)
* Класс [ISvgImage](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)