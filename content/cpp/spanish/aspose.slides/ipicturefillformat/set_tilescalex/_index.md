---
title: set_TileScaleX()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece la escala horizontal para el relleno de textura como un porcentaje. Escribe float.
type: docs
weight: 339
url: /es/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) método


Establece la escala horizontal para el relleno de textura como un porcentaje. Escribe **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
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

* Clase [IPictureFillFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)