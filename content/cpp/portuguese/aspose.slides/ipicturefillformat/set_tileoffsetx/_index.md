---
title: set_TileOffsetX()
second_title: Referência da API Aspose.Slides para C++
description: Define o deslocamento horizontal da textura a partir da origem da forma em pontos. Um valor positivo move a textura para a direita, enquanto um valor negativo a move para a esquerda. Escreva float.
type: docs
weight: 287
url: /pt/aspose.slides/ipicturefillformat/set_tileoffsetx/
---
## IPictureFillFormat::set_TileOffsetX(float) método


Define o deslocamento horizontal da textura a partir da origem da forma em pontos. Um valor positivo move a textura para a direita, enquanto um valor negativo a move para a esquerda. Escreva **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetX(float value)=0
```

## Observações



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o formato de preenchimento da imagem da forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Define o modo de preenchimento da imagem para Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Define o deslocamento horizontal da textura para 20 pontos
pictureFillFormat->set_TileOffsetX(20.0f);
```

## Veja Também

* Classe [IPictureFillFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)