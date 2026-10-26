---
title: get_TileAlignment()
second_title: Referência da API Aspose.Slides para C++
description: Retorna como a textura está alinhada dentro da forma. Esta configuração controla o ponto de partida do padrão de textura e como ele se repete ao longo da forma. Leia RectangleAlignment.
type: docs
weight: 378
url: /pt/aspose.slides/ipicturefillformat/get_tilealignment/
---
## IPictureFillFormat::get_TileAlignment() método

Retorna como a textura está alinhada dentro da forma. Esta configuração controla o ponto de partida do padrão de textura e como ele se repete ao longo da forma. Leia [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual RectangleAlignment Aspose::Slides::IPictureFillFormat::get_TileAlignment()=0
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

// Define o alinhamento do ladrilhamento para a parte inferior direita
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Veja Também

* Enum [RectangleAlignment](../../rectanglealignment/)
* Classe [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)