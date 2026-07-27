---
title: set_TileFlip()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Voltea la losa de textura alrededor de su eje horizontal, vertical o ambos. Escribe Slides::TileFlip."
type: docs
weight: 417
url: /es/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) método


Voltea la losa de textura alrededor de su eje horizontal, vertical o ambos. Escribe [Slides::TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
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

// Voltea la losa de textura alrededor de su eje vertical.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Véase también

* Enum [TileFlip](../../tileflip/)
* Clase [IPictureFillFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)