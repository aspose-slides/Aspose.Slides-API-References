---
title: set_TileFlip()
second_title: Referência da API Aspose.Slides para C++
description: "Inverte o ladrilho de textura ao redor do seu eixo horizontal, vertical ou ambos os eixos. Escreva Slides::TileFlip."
type: docs
weight: 417
url: /pt/aspose.slides/ipicturefillformat/set_tileflip/
---
## IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) método

Inverte o ladrilho de textura ao redor do seu eixo horizontal, vertical ou ambos os eixos. Escreva [Slides::TileFlip](../../tileflip/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value)=0
```

## Observações

O padrão é [TileFlip::NoFlip](../../tileflip/).

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o formato de preenchimento de imagem da forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Define o modo de preenchimento de imagem como Ladrilho
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Inverte o ladrilho de textura ao redor de seu eixo vertical.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
}
```

## Ver Também

* Enum [TileFlip](../../tileflip/)
* Classe [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)