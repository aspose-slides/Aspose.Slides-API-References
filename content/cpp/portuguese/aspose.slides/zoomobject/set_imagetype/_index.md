---
title: set_ImageType()
second_title: Referência da API Aspose.Slides para C++
description: "Define o tipo de imagem de um objeto de zoom. Use ZoomImageType. Valor padrão: Preview"
type: docs
weight: 14
url: /pt/aspose.slides/zoomobject/set_imagetype/
---
## ZoomObject::set_ImageType(ZoomImageType) método

Define o tipo de imagem de um objeto de zoom. Escreva [ZoomImageType](../../zoomimagetype/). Valor padrão: Preview

```cpp
void Aspose::Slides::ZoomObject::set_ImageType(ZoomImageType value) override
```

## Observações

Especifica se o objeto Zoom está usando a visualização do slide ou uma imagem de capa.

O próximo exemplo demonstra a alteração do Tipo de Imagem para o valor Preview. Neste caso, a imagem atual de um objeto Zoom muda para a imagem do slide: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto image = pres->get_Images()->AddImage(Image::FromFile(u"image.png"));
auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1), image);
zoomFrame->set_ImageType(ZoomImageType::Preview);
```

## Veja Também

* Enum [ZoomImageType](../../zoomimagetype/)
* Classe [ZoomObject](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)