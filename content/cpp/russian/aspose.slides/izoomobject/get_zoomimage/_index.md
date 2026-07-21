---
title: get_ZoomImage()
second_title: Aspose.Slides для C++ справочник API
description: Получает изображение для объекта масштабирования. Читайте IPPImage.
type: docs
weight: 79
url: /ru/aspose.slides/izoomobject/get_zoomimage/
---
## IZoomObject::get_ZoomImage() метод


Получает изображение для объекта масштабирования. Читайте [IPPImage](../../ippimage/).

```cpp
virtual System::SharedPtr<IPPImage> Aspose::Slides::IZoomObject::get_ZoomImage()=0
```

## Примечания


В примере демонстрируется изменение изображения объекта Zoom: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IPPImage](../../ippimage/)
* Класс [IZoomObject](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)