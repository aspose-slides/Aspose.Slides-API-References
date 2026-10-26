---
title: get_TileFlip()
second_title: Referência da API Aspose.Slides para C++
description: "Inverte o mosaico de textura ao redor de seu eixo horizontal, vertical ou ambos. Leia Slides::TileFlip."
type: docs
weight: 404
url: /pt/aspose.slides/picturefillformat/get_tileflip/
---
## PictureFillFormat::get_TileFlip() método

Inverte o mosaico de textura ao redor de seu eixo horizontal, vertical ou ambos. Leia [Slides::TileFlip](../../tileflip/).

```cpp
Aspose::Slides::TileFlip Aspose::Slides::PictureFillFormat::get_TileFlip() override
```

## Observações

O padrão é [TileFlip::NoFlip](../../tileflip/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o formato de preenchimento de imagem da forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Define o modo de preenchimento de imagem como Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Inverte o mosaico de textura ao redor de seu eixo vertical.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Ver também

* Enum [TileFlip](../../tileflip/)
* Classe [PictureFillFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)