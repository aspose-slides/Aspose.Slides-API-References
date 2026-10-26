---
title: set_ZoomImage()
second_title: Aspose.Slides для C++ справка по API
description: Устанавливает изображение для объекта масштабирования. Запишите IPPImage.
type: docs
weight: 92
url: /ru/aspose.slides/izoomobject/set_zoomimage/
---
## IZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) метод

Устанавливает изображение для объекта масштабирования. Запишите [IPPImage](../../ippimage/).

```cpp
virtual void Aspose::Slides::IZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value)=0
```

## Примечания

Пример демонстрирует изменение изображения объекта Zoom:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IPPImage](../../ippimage/)
* Класс [IZoomObject](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)