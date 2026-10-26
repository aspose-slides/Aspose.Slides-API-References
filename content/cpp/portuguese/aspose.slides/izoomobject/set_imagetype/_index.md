---
title: set_ImageType()
second_title: Referência da API Aspose.Slides para C++
description: "Define o tipo de imagem de um objeto de zoom. Escreva ZoomImageType. Valor padrão: Preview"
type: docs
weight: 14
url: /pt/aspose.slides/izoomobject/set_imagetype/
---
## IZoomObject::set_ImageType(ZoomImageType) método

Define o tipo de imagem de um objeto de zoom. Escreva [ZoomImageType](../../zoomimagetype/). Valor padrão: Preview

```cpp
virtual void Aspose::Slides::IZoomObject::set_ImageType(ZoomImageType value)=0
```

## Observações

Especifica se o objeto Zoom está usando a pré-visualização do slide ou uma imagem de capa. 

Este exemplo demonstra a mudança do Image Type para o valor Preview. Nesse caso, a imagem atual de um objeto Zoom muda para a imagem do slide: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Ver Também

* Enum [ZoomImageType](../../zoomimagetype/)
* classe [IZoomObject](../)
* namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)