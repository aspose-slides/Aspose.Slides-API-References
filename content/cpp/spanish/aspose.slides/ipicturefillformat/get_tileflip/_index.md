---
title: get_TileFlip()
second_title: Referencia de API de Aspose.Slides para C++
description: "Voltea la loseta de textura alrededor de su eje horizontal, vertical o ambos ejes. Lea Slides::TileFlip."
type: docs
weight: 404
url: /es/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() método


Voltea la loseta de textura alrededor de su eje horizontal, vertical o ambos ejes. Lea [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
```

## Observaciones


El valor predeterminado es [TileFlip::NoFlip](../../tileflip/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtiene el formato de relleno de imagen de la forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Establece el modo de relleno de imagen a Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Voltea la loseta de textura alrededor de su eje vertical.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Ver también

* Enumeración [TileFlip](../../tileflip/)
* Clase [IPictureFillFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)