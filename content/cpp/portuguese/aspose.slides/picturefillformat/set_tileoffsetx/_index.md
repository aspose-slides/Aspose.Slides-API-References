---
title: set_TileOffsetX()
second_title: Referência da API Aspose.Slides para C++
description: Define o deslocamento horizontal da textura a partir da origem da forma em pontos. Um valor positivo move a textura para a direita, enquanto um valor negativo a move para a esquerda. Escreva float.
type: docs
weight: 287
url: /pt/aspose.slides/picturefillformat/set_tileoffsetx/
---
## PictureFillFormat::set_TileOffsetX(float) método

Define o deslocamento horizontal da textura a partir da origem da forma em pontos. Um valor positivo move a textura para a direita, enquanto um valor negativo a move para a esquerda. Escreva **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileOffsetX(float value) override
```

## Observações



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o formato de preenchimento de imagem da forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Define o modo de preenchimento de imagem como Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Define o deslocamento horizontal da textura para 20 pontos
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Ver também

* Classe [PictureFillFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)