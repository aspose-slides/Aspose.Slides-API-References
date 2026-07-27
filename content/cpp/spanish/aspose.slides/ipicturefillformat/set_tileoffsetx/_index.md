---
title: set_TileOffsetX()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece la compensación horizontal de la textura desde el origen de la forma en puntos. Un valor positivo desplaza la textura a la derecha, mientras que un valor negativo la desplaza a la izquierda. Escribe float.
type: docs
weight: 287
url: /es/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) método


Establece la compensación horizontal de la textura desde el origen de la forma en puntos. Un valor positivo desplaza la textura a la derecha, mientras que un valor negativo la desplaza a la izquierda. Escribe **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
```

## Observaciones



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtiene el formato de relleno de imagen de la forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Establece el modo de relleno de imagen a Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Establece la compensación horizontal de la textura a 20 puntos
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Ver también

* Clase [IPictureFillFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)