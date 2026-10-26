---
title: set_TileFlip()
second_title: Referência da API Aspose.Slides para C++
description: "Inverte o azulejo de textura ao redor de seu eixo horizontal, vertical ou ambos. Escreva Slides::TileFlip."
type: docs
weight: 417
url: /pt/aspose.slides/picturefillformat/set_tileflip/
---
## PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip) método


Inverte o azulejo de textura ao redor de seu eixo horizontal, vertical ou ambos. Escreva [Slides::TileFlip](../../tileflip/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileFlip(Aspose::Slides::TileFlip value) override
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

// Inverte o azulejo de textura ao redor de seu eixo vertical.
pictureFillFormat->set_TileFlip(TileFlip::FlipY);
```

## Veja Também

* Enum [TileFlip](../../tileflip/)
* Classe [PictureFillFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)