---
title: get_TileOffsetX()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el desplazamiento horizontal de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura hacia la derecha, mientras que un valor negativo la mueve hacia la izquierda. Lectura float.
type: docs
weight: 274
url: /es/aspose.slides/ipicturefillformat/get_tileoffsetx/
---
## IPictureFillFormat::get_TileOffsetX() método


Devuelve el desplazamiento horizontal de la textura desde el origen de la forma en puntos. Un valor positivo mueve la textura hacia la derecha, mientras que un valor negativo la mueve hacia la izquierda. Lectura **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetX()=0
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

* Clase [IPictureFillFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)