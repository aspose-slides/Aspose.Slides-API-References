---
title: get_TileScaleY()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve la escala vertical para el relleno de textura como un porcentaje. Leer float.
type: docs
weight: 352
url: /es/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() método


Devuelve la escala vertical para el relleno de textura como un porcentaje. Leer **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
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

* Clase [IPictureFillFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)