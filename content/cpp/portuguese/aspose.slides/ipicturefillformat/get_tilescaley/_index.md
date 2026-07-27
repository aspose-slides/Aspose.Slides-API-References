---
title: get_TileScaleY()
second_title: Referência da API Aspose.Slides para C++
description: Retorna a escala vertical do preenchimento de textura como porcentagem. Leitura float.
type: docs
weight: 352
url: /pt/aspose.slides/ipicturefillformat/get_tilescaley/
---
## IPictureFillFormat::get_TileScaleY() método


Retorna a escala vertical para o preenchimento de textura como porcentagem. Leitura **float**.

```cpp
virtual float Aspose::Slides::IPictureFillFormat::get_TileScaleY()=0
```

## Observações



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<ISlide> slide = presentation->get_Slide(0);

// Obtém o formato de preenchimento de imagem da forma
System::SharedPtr<IPictureFillFormat> pictureFillFormat = slide->get_Shape(0)->get_FillFormat()->get_PictureFillFormat();

// Define o modo de preenchimento de imagem para Tile
pictureFillFormat->set_PictureFillMode(PictureFillMode::Tile);

// Define a escala vertical da textura para 120 por cento
pictureFillFormat->set_TileScaleY(120.0f);
```

## Ver também

* Classe [IPictureFillFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)