---
title: get_ImageType()
second_title: Referencia de API de Aspose.Slides para C++
description: "Obtiene el tipo de imagen de un objeto de zoom. Lea ZoomImageType. Valor predeterminado: Preview"
type: docs
weight: 1
url: /es/aspose.slides/izoomobject/get_imagetype/
---
## IZoomObject::get_ImageType() método


Obtiene el tipo de imagen de un objeto de zoom. Lea [ZoomImageType](../../zoomimagetype/). Valor predeterminado: Preview

```cpp
virtual ZoomImageType Aspose::Slides::IZoomObject::get_ImageType()=0
```

## Observaciones


Especifica si el objeto Zoom está usando la vista previa de la diapositiva o una imagen de portada. 

Este ejemplo muestra cómo cambiar Image Type al valor Preview. En este caso la imagen actual de un objeto Zoom cambia a la imagen de la diapositiva: 
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