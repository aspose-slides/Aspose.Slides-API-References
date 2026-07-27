---
title: get_ImageType()
second_title: Referência da API Aspose.Slides para C++
description: "Obtém o tipo de imagem de um objeto de zoom. Leia ZoomImageType. Valor padrão: Preview"
type: docs
weight: 1
url: /pt/aspose.slides/izoomobject/get_imagetype/
---
## IZoomObject::get_ImageType() método

Obtém o tipo de imagem de um objeto de zoom. Leia [ZoomImageType](../../zoomimagetype/). Valor padrão: Preview

```cpp
virtual ZoomImageType Aspose::Slides::IZoomObject::get_ImageType()=0
```

## Observações

Especifica se o objeto Zoom está usando o slide Preview ou uma imagem de capa. 

Este exemplo demonstra a mudança de Image Type para o valor Preview. Nesse caso a imagem atual de um objeto Zoom muda para a imagem do slide: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Veja Também

* Enum [ZoomImageType](../../zoomimagetype/)
* Classe [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)