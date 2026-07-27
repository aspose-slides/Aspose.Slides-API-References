---
title: set_TileAlignment()
second_title: Referência da API Aspose.Slides para C++
description: Define como a textura é alinhada dentro da forma. Esta configuração controla o ponto de partida do padrão de textura e como ele se repete ao longo da forma. Escreva RectangleAlignment.
type: docs
weight: 391
url: /pt/aspose.slides/ipicturefillformat/set_tilealignment/
---
## IPictureFillFormat::set_TileAlignment(RectangleAlignment) método


Define como a textura é alinhada dentro da forma. Esta configuração controla o ponto de partida do padrão de textura e como ele se repete ao longo da forma. Escreva [RectangleAlignment](../../rectanglealignment/).

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileAlignment(RectangleAlignment value)=0
```

## Observações


O padrão é [RectangleAlignment::TopLeft](../../rectanglealignment/). 


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o formato de preenchimento de imagem da forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Define o modo de preenchimento de imagem para Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Define o alinhamento do ladrilhamento para o canto inferior direito
pictureFillFormat->set_TileAlignment(RectangleAlignment::BottomRight);
```

## Ver também

* Enumeração [RectangleAlignment](../../rectanglealignment/)
* Classe [IPictureFillFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)