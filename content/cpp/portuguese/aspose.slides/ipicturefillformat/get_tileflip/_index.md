---
title: get_TileFlip()
second_title: Referência da API Aspose.Slides para C++
description: "Inverte o ladrilho da textura ao redor de seu eixo horizontal, vertical ou ambos os eixos. Leia Slides::TileFlip."
type: docs
weight: 404
url: /pt/aspose.slides/ipicturefillformat/get_tileflip/
---
## IPictureFillFormat::get_TileFlip() método

Inverte o ladrilho da textura ao redor de seu eixo horizontal, vertical ou ambos. Consulte [Slides::TileFlip](../../tileflip/).

```cpp
virtual Aspose::Slides::TileFlip Aspose::Slides::IPictureFillFormat::get_TileFlip()=0
```

## Observações

O padrão é [TileFlip::NoFlip](../../tileflip/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o formato de preenchimento de imagem da forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Define o modo de preenchimento da imagem como Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Inverte o ladrilho da textura ao redor de seu eixo vertical.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Veja também

* Enum [TileFlip](../../tileflip/)
* Classe [IPictureFillFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)