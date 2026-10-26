---
title: set_TileScaleX()
second_title: Referência da API Aspose.Slides para C++
description: Define a escala horizontal do preenchimento de textura como uma porcentagem. Escreva float.
type: docs
weight: 339
url: /pt/aspose.slides/ipicturefillformat/set_tilescalex/
---
## IPictureFillFormat::set_TileScaleX(float) método


Define a escala horizontal do preenchimento de textura como uma porcentagem. Escreva **float**.

```cpp
virtual void Aspose::Slides::IPictureFillFormat::set_TileScaleX(float value)=0
```

## Observações



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o formato de preenchimento de imagem da forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Define o modo de preenchimento de imagem como Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Define a escala horizontal da textura para 120 por cento
pictureFillFormat->set_TileScaleX(120.0f);
```

## Veja também

* Classe [IPictureFillFormat](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)