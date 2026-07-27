---
title: set_TileFlip()
second_title: Referencia de API de Aspose.Slides para C++
description: "Gira la loseta de textura alrededor de su eje horizontal, vertical o ambos ejes. Escriba Slides::TileFlip."
type: docs
weight: 417
url: /es/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) método


Gira la loseta de textura alrededor de su eje horizontal, vertical o ambos ejes. Escribe [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
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

// Gira la loseta de textura alrededor de su eje vertical.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Ver también

* Enumeración [TileFlip](../../tileflip/)
* Clase [PictureFillFormat](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)