---
title: set_TileScaleY()
second_title: Referência da API Aspose.Slides para C++
description: Define a escala vertical para o preenchimento de textura como uma porcentagem. Escreva float.
type: docs
weight: 365
url: /pt/aspose.slides/picturefillformat/set_tilescaley/
---
## PictureFillFormat::set_TileScaleY(float) método


Define a escala vertical para o preenchimento de textura como uma porcentagem. Escreva **float**.

```cpp
void Aspose::Slides::PictureFillFormat::set_TileScaleY(float value) override
```

## Observações



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o formato de preenchimento de imagem da forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Define o modo de preenchimento de imagem como Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Define a escala vertical da textura para 120 por cento
pictureFillFormat->set_TileScaleY(120.0f);
```

## Ver também

* Classe [PictureFillFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)