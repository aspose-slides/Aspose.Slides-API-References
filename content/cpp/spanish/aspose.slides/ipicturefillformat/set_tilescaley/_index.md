---
title: set_TileScaleY()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece la escala vertical para el relleno de textura como un porcentaje. Escriba float.
type: docs
weight: 365
url: /es/aspose.slides/ipicturefillformat/set_tilescaley/
---
## IPictureFillFormat::set_TileScaleY(float) método

Establece la escala vertical para el relleno de textura como un porcentaje. Escriba **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleY(float value)=0
```

## Observaciones



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtiene el formato de relleno de imagen de la forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Establece el modo de relleno de imagen en Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Establece la escala vertical de la textura al 120 por ciento
pictureFillFormat->set_TileScaleY(120.0f);
```

## Ver también

* Clase [IPictureFillFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)