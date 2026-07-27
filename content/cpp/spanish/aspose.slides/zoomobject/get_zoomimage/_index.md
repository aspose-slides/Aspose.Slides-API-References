---
title: get_ZoomImage()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene la imagen del objeto Zoom. Lea IPPImage.
type: docs
weight: 79
url: /es/aspose.slides/zoomobject/get_zoomimage/
---
## ZoomObject::get_ZoomImage() método


Obtiene la imagen del objeto Zoom. Lea [IPPImage](../../ippimage/).

```cpp
System::SharedPtr<IPPImage> Aspose::Slides::ZoomObject::get_ZoomImage() override
```

## Observaciones


El ejemplo muestra cómo cambiar la imagen de un objeto Zoom: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slide(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slide(1));
System::SharedPtr<IPPImage> image = pres->get_Images()->AddImage(System::Drawing::Image::FromFile(u"image.png"));
zoomFrame->set_ZoomImage(image);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IPPImage](../../ippimage/)
* Clase [ZoomObject](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)