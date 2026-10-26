---
title: set_ZoomImage()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece la imagen para el objeto de zoom. Escriba IPPImage.
type: docs
weight: 92
url: /es/aspose.slides/zoomobject/set_zoomimage/
---
## ZoomObject::set_ZoomImage(System::SharedPtr\<IPPImage\>) método

Establece la imagen para el objeto de zoom. Escriba [IPPImage](../../ippimage/).

```cpp
void Aspose::Slides::ZoomObject::set_ZoomImage(System::SharedPtr<IPPImage> value) override
```

## Comentarios

El ejemplo demuestra cómo cambiar la imagen de un objeto Zoom:
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
* Biblioteca [Aspose.Slides](../../../)