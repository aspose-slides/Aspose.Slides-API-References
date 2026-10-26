---
title: set_TileScaleX()
second_title: Referencia API de Aspose.Slides para C++
description: Establece la escala horizontal para el relleno de textura como un porcentaje. Escriba float.
type: docs
weight: 339
url: /es/aspose.slides/picturefillformat/set_tilescalex/
---
## PictureFillFormat::set_TileScaleX(float) método


Establece la escala horizontal para el relleno de textura como un porcentaje. Escriba **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleX(float value) override
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