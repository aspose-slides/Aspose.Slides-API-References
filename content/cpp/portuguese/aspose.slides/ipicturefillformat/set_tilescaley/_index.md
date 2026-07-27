---
title: set_TileScaleY()
second_title: Referência da API Aspose.Slides para C++
description: Define a escala vertical para o preenchimento de textura como uma porcentagem. Escreva float.
type: docs
weight: 365
url: /pt/aspose.slides/ipicturefillformat/set_tilescaley/
---
## IPictureFillFormat::set_TileScaleY(float) método


Define a escala vertical para o preenchimento de textura como uma porcentagem. Escreva **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleY(float value)=0
```

## Observações



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o formato de preenchimento da imagem da forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Define o modo de preenchimento da imagem como Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Define a escala vertical da textura para 120 por cento
pictureFillFormat->set_TileScaleY(120.0f);
```

## Veja Também

* Classe [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)