---
title: set_TileOffsetY()
second_title: Referência da API Aspose.Slides para C++
description: Define o deslocamento vertical da textura a partir da origem da forma em pontos. Um valor positivo move a textura para baixo, enquanto um valor negativo a move para cima. Escreva float.
type: docs
weight: 313
url: /pt/aspose.slides/ipicturefillformat/set_tileoffsety/
---
## IPictureFillFormat::set_TileOffsetY(float) método


Define o deslocamento vertical da textura a partir da origem da forma em pontos. Um valor positivo move a textura para baixo, enquanto um valor negativo a move para cima. Escreva **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileOffsetY(float value)=0
```

## Observações



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o formato de preenchimento de imagem da forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Define o modo de preenchimento de imagem como Ladrilho
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Define o deslocamento vertical da textura para -50 pontos
pictureFillFormat->set_TileOffsetY(-50.0f);
```

## Veja também

* Classe [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)