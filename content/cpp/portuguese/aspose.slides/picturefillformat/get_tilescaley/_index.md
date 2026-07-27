---
title: get_TileScaleY()
second_title: Referência API do Aspose.Slides para C++
description: Retorna a escala vertical para o preenchimento de textura como uma porcentagem. Lê float.
type: docs
weight: 352
url: /pt/aspose.slides/picturefillformat/get_tilescaley/
---
## PictureFillFormat::get_TileScaleY() método

Retorna a escala vertical para o preenchimento de textura como uma porcentagem. Lê **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleY() override
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

## Ver também

* Classe [PictureFillFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)