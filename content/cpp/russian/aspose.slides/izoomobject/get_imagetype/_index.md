---
title: get_ImageType()
second_title: Aspose.Slides для C++ справочник API
description: "Получает тип изображения объекта зума. См. ZoomImageType. Значение по умолчанию: Preview"
type: docs
weight: 1
url: /ru/aspose.slides/izoomobject/get_imagetype/
---
## IZoomObject::get_ImageType() метод

Получает тип изображения объекта зума. См. [ZoomImageType](../../zoomimagetype/). Значение по умолчанию: Preview

```cpp
virtual ZoomImageType Aspose::Slides::IZoomObject::get_ImageType()=0
```

## Примечания

Указывает, использует ли объект Zoom предварительный просмотр слайда или изображение обложки.

В этом примере демонстрируется изменение Image Type на значение Preview. В этом случае текущее изображение объекта Zoom меняется на изображение слайда: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Смотрите также

* Перечисление [ZoomImageType](../../zoomimagetype/)
* Класс [IZoomObject](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)