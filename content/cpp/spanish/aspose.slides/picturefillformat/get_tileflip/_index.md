---
title: get_TileFlip()
second_title: Referencia de API de Aspose.Slides para C++
description: "Voltea la loseta de textura alrededor de su eje horizontal, vertical o ambos ejes. Lea Slides::TileFlip."
type: docs
weight: 404
url: /es/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() método


Voltea la loseta de textura alrededor de su eje horizontal, vertical o ambos ejes. Lea [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## Observaciones


El valor predeterminado es [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtiene el formato de relleno de imagen de la forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Establece el modo de relleno de imagen a Mosaico
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Voltea la loseta de textura alrededor de su eje vertical.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Ver también

* Enum [TileFlip](../../tileflip/)
* Clase [PictureFillFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)