---
title: set_ZoomImage()
second_title: Aspose.Slides для C++: справочник API
description: Устанавливает изображение для объекта масштабирования. Запишите IPPImage.
type: docs
weight: 92
url: /ru/aspose.slides/zoomobject/set_zoomimage/
---
## ZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) метод


Устанавливает изображение для объекта масштабирования. Запишите [IPPImage](../../ippimage/).

```cpp
void Aspose::Slides::ZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value) override
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

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IPPImage](../../ippimage/)
* Класс [ZoomObject](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)