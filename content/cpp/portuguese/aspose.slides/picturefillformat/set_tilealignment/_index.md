---
title: set_TileAlignment()
second_title: Aspose.Slides para C++ Referência da API
description: Define como a textura é alinhada dentro da forma. Essa configuração controla o ponto de partida do padrão de textura e como ele se repete ao longo da forma. Escreva RectangleAlignment.
type: docs
weight: 391
url: /pt/aspose.slides/picturefillformat/set_tilealignment/
---
## PictureFillFormat::set_TileAlignment(RectangleAlignment) método


Define como a textura é alinhada dentro da forma. Esta configuração controla o ponto de partida do padrão de textura e como ele se repete ao longo da forma. Escreva [RectangleAlignment](../../rectanglealignment/).

```cpp
void Aspose::Slides::PictureFillFormat::set_TileAlignment(RectangleAlignment value) override
```

## Observações


O padrão é [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o formato de preenchimento de imagem da forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Define o modo de preenchimento de imagem como Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Define o alinhamento do ladrilho para a parte inferior direita
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Veja Também

* Enum [RectangleAlignment](../../rectanglealignment/)
* Classe [PictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)