---
title: get_ShowBackground()
second_title: Aspose.Slides para C++ Referência da API
description: "Obtém o valor que especifica se o Zoom usará o plano de fundo do slide de destino. Leia bool. Valor padrão: true"
type: docs
weight: 53
url: /pt/aspose.slides/izoomobject/get_showbackground/
---
## IZoomObject::get_ShowBackground() método


Obtém o valor que especifica se o Zoom usará o plano de fundo do slide de destino. Leia **bool**. Valor padrão: true

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ShowBackground()=0
```

## Observações


O exemplo demonstra a remoção do plano de fundo de uma imagem de um objeto Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Veja Também

* Classe [IZoomObject](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)