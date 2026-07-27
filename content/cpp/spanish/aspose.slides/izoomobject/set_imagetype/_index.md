---
title: set_ImageType()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Establece el tipo de imagen de un objeto de zoom. Escriba ZoomImageType. Valor predeterminado: Preview"
type: docs
weight: 14
url: /es/aspose.slides/izoomobject/set_imagetype/
---
## IZoomObject::set_ImageType(ZoomImageType) método

Establece el tipo de imagen de un objeto de zoom. Escriba [ZoomImageType](../../zoomimagetype/). Valor predeterminado: Preview

```cpp
virtual void Aspose::Slides::IZoomObject::set_ImageType(ZoomImageType value)=0
```

## Observaciones

Especifica si el objeto Zoom está usando la vista previa de la diapositiva o una imagen de portada.

Este ejemplo muestra cómo cambiar Image Type al valor Preview. En este caso, la imagen actual de un objeto Zoom cambia a la imagen de la diapositiva:
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Ver también

* Enumeración [ZoomImageType](../../zoomimagetype/)
* Clase [IZoomObject](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)