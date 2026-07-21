---
title: get_ZoomImage()
second_title: Справочник API Aspose.Slides для C++
description: Получает изображение для объекта Zoom. См. IPPImage.
type: docs
weight: 79
url: /ru/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() method


Получает изображение для объекта Zoom. См. [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPPImage](../../ippimage/)
* Class [ZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)