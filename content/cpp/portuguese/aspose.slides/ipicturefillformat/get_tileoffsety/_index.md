---
title: get_TileOffsetY()
second_title: Aspose.Slides para C++ Referência da API
description: Retorna o deslocamento vertical da textura a partir da origem da forma em pontos. Um valor positivo move a textura para baixo, enquanto um valor negativo a move para cima. Leitura float.
type: docs
weight: 300
url: /pt/aspose.slides/ipicturefillformat/get_tileoffsety/
---
## IPictureFillFormat::get_TileOffsetY() método


Retorna o deslocamento vertical da textura a partir da origem da forma em pontos. Um valor positivo move a textura para baixo, enquanto um valor negativo a move para cima. Leitura **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileOffsetY()=0
```

## Observações



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o formato de preenchimento da imagem da forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Define o modo de preenchimento da imagem como Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Define o deslocamento vertical da textura para -50 pontos
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Veja Também

* Classe [IPictureFillFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)