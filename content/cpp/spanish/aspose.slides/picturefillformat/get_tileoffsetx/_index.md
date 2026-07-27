---
title: get_TileOffsetX()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el desplazamiento horizontal de la textura respecto al origen de la forma en puntos. Un valor positivo mueve la textura a la derecha, mientras que un valor negativo la mueve a la izquierda. Solo lectura float.
type: docs
weight: 274
url: /es/aspose.slides/picturefillformat/get_tileoffsetx/
---
## PictureFillFormat::get_TileOffsetX() método


Devuelve el desplazamiento horizontal de la textura respecto al origen de la forma en puntos. Un valor positivo mueve la textura a la derecha, mientras que un valor negativo la mueve a la izquierda. Solo lectura **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileOffsetX() override
```

## Observaciones



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtiene el formato de relleno de imagen de la forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Establece el modo de relleno de imagen a Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Establece el desplazamiento horizontal de la textura a 20 puntos
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Ver también

* Clase [PictureFillFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)