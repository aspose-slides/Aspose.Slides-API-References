---
title: set_ReturnToParent()
second_title: Referência da API Aspose.Slides para C++
description: "Define o comportamento de navegação na apresentação de slides. Escreva bool. Valor padrão: false"
type: docs
weight: 40
url: /pt/aspose.slides/izoomobject/set_returntoparent/
---
## IZoomObject::set_ReturnToParent(bool) método


Define o comportamento de navegação na apresentação de slides. Escreva **bool**. Valor padrão: false

```cpp
virtual void Aspose::Slides::IZoomObject::set_ReturnToParent(bool value)=0
```

## Observações


O valor true da propriedade especifica o comportamento de navegação de retorno ao pai na apresentação de slides. 

Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Veja também

* Classe [IZoomObject](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)