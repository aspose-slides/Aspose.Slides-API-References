---
title: get_TileScaleY()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve la escala vertical para el relleno de textura como un porcentaje. Lectura float.
type: docs
weight: 352
url: /es/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() método


Devuelve la escala vertical para el relleno de textura como un porcentaje. Lectura **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
```

## Observaciones



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtiene el formato de relleno de imagen de la forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Establece el modo de relleno de imagen a Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Establece la escala vertical para la textura al 120 por ciento
pictureFillFormat->set_TileScaleY(120.0f);
```

## Ver también

* Clase [PictureFillFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)