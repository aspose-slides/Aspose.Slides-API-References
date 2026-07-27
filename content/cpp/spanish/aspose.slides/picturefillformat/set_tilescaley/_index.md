---
title: set_TileScaleY()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece la escala vertical para el relleno de textura como un porcentaje. Escribe float.
type: docs
weight: 365
url: /es/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) método


Establece la escala vertical para el relleno de textura como un porcentaje. Escribe **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## Observaciones



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtiene el formato de relleno de imagen de la forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Establece el modo de relleno de imagen a Mosaico
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Establece la escala vertical de la textura al 120 por ciento
pictureFillFormat->set_TileScaleY(120.0f);
```

## Ver también

* Clase [PictureFillFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)