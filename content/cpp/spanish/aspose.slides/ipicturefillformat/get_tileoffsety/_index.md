---
title: get_TileOffsetY()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el desplazamiento vertical de la textura desde el origen de la forma en puntos. Un valor positivo desplaza la textura hacia abajo, mientras que un valor negativo la desplaza hacia arriba. Lectura float.
type: docs
weight: 300
url: /es/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() método

Devuelve el desplazamiento vertical de la textura desde el origen de la forma en puntos. Un valor positivo desplaza la textura hacia abajo, mientras que un valor negativo la desplaza hacia arriba. Lectura **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
```

## Comentarios

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtiene el formato de relleno de imagen de la forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Establece el modo de relleno de imagen a Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Establece el desplazamiento vertical de la textura a -50 puntos
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Ver también

* Clase [IPictureFillFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)