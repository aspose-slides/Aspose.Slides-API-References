---
title: get_TileScaleX()
second_title: Aspose.Slides para C++ Referencia de API
description: Devuelve la escala horizontal del relleno de textura como un porcentaje. Lectura float.
type: docs
weight: 326
url: /es/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() método


Devuelve la escala horizontal del relleno de textura como un porcentaje. Lectura **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## Observaciones



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtiene el formato de relleno de imagen de la forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Establece el modo de relleno de imagen a Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Establece la escala horizontal de la textura al 120 por ciento
pictureFillFormat->set_TileScaleX(120.0f);
```

## Ver también

* Clase [PictureFillFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)