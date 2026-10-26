---
title: set_TileOffsetY()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece el desplazamiento vertical de la textura desde el origen de la forma en puntos. Un valor positivo desplaza la textura hacia abajo, mientras que un valor negativo la desplaza hacia arriba. Escriba float.
type: docs
weight: 313
url: /es/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) método


Establece el desplazamiento vertical de la textura desde el origen de la forma en puntos. Un valor positivo desplaza la textura hacia abajo, mientras que un valor negativo la desplaza hacia arriba. Escriba **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## Observaciones



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