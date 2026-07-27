---
title: get_TileScaleX()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a escala horizontal do preenchimento de textura como porcentagem. Leitura float.
type: docs
weight: 326
url: /pt/aspose.slides/picturefillformat/get_tilescalex/
---
## PictureFillFormat::get_TileScaleX() método


Retorna a escala horizontal do preenchimento de textura como porcentagem. Leitura **float**.

```cpp
float Aspose::Slides::PictureFillFormat::get_TileScaleX() override
```

## Observações



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o formato de preenchimento de imagem da forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Define o modo de preenchimento de imagem para Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Define a escala horizontal da textura para 120 por cento
pictureFillFormat->set_TileScaleX(120.0f);
```

## Ver também

* Classe [PictureFillFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)