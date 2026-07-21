---
title: set_ImageType()
second_title: Aspose.Slides для C++ справочник API
description: "Устанавливает тип изображения Zoom-объекта. Укажите ZoomImageType. Значение по умолчанию: Preview"
type: docs
weight: 14
url: /ru/aspose.slides/izoomobject/set_imagetype/
---
## IZoomObject::set_ImageType(ZoomImageType) метод


Устанавливает тип изображения Zoom-объекта. Пишите [ZoomImageType](../../zoomimagetype/). Значение по умолчанию: Preview

```cpp
virtual void Aspose::Slides::IZoomObject::set_ImageType(ZoomImageType value)=0
```

## Примечания


Указывает, использует ли объект Zoom предварительный просмотр слайда или изображение обложки. 

В этом примере показано изменение Image Type на значение Preview. В этом случае текущее изображение объекта Zoom меняется на изображение слайда: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## См. также

* Перечисление [ZoomImageType](../../zoomimagetype/)
* Класс [IZoomObject](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)