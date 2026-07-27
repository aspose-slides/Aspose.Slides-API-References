---
title: set_ShowBackground()
second_title: Aspose.Slides para C++ Referência da API
description: "Define o valor que especifica se o Zoom usará o plano de fundo do slide de destino. Escreva bool. Valor padrão: true"
type: docs
weight: 66
url: /pt/aspose.slides/izoomobject/set_showbackground/
---
## IZoomObject::set_ShowBackground(bool) método

Define o valor que especifica se o Zoom usará o plano de fundo do slide de destino. Escreva **bool**. Valor padrão: true

```cpp
virtual void Aspose::Slides::IZoomObject::set_ShowBackground(bool value)=0
```

## Observações

O exemplo demonstra a remoção do plano de fundo de uma imagem de um objeto Zoom: 
```cpp
auto pres = System::MakeObject<Presentation>();
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ShowBackground(false);
```

## Ver Também

* Classe [IZoomObject](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)