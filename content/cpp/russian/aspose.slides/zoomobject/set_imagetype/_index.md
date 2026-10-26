---
title: set_ImageType()
second_title: Справочник API Aspose.Slides для C++
description: "Устанавливает тип изображения объекта Zoom. Запишите ZoomImageType. Значение по умолчанию: Preview"
type: docs
weight: 14
url: /ru/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType(ZoomImageType) метод


Устанавливает тип изображения объекта Zoom. Запишите [ZoomImageType](../../zoomimagetype/). Значение по умолчанию: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## Примечания


Указывает, использует ли объект Zoom предварительный просмотр слайда или изображение обложки. 

Следующий пример демонстрирует изменение Image Type на значение Preview. В этом случае текущий образ объекта Zoom меняется на изображение слайда: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Смотрите также

* Перечисление [ZoomImageType](../../zoomimagetype/)
* Класс [ZoomObject](../)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)