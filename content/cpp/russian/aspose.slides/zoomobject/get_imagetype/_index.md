---
title: get_ImageType()
second_title: Aspose.Slides для C++ API справка
description: "Получает тип изображения объекта Zoom. Читайте ZoomImageType. Значение по умолчанию: Preview"
type: docs
weight: 1
url: /ru/aspose.slides/zoomobject/get_imagetype/
---
## ZoomObject::get_ImageType() method

Получает тип изображения объекта Zoom. Читайте [ZoomImageType](../../zoomimagetype/). Значение по умолчанию: Preview

```cpp
ZoomImageType Aspose::Slides::ZoomObject::get_ImageType() override
```

## Примечания

Указывает, использует ли объект Zoom предварительный просмотр слайда или изображение обложки.

Следующий пример демонстрирует изменение Image Type на значение Preview. В этом случае текущее изображение объекта Zoom меняется на изображение слайда:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## См. также

* Enum [ZoomImageType](../../zoomimagetype/)
* Class [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)