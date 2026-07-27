---
title: get_ReturnToParent()
second_title: Aspose.Slides para C++ Referência da API
description: "Obtém o comportamento de navegação na apresentação de slides. Leia bool. Valor padrão: false"
type: docs
weight: 27
url: /pt/aspose.slides/izoomobject/get_returntoparent/
---
## IZoomObject::get_ReturnToParent() método

Obtém o comportamento de navegação na apresentação de slides. Leia **bool**. Valor padrão: false

```cpp
virtual bool Aspose::Slides::IZoomObject::get_ReturnToParent()=0
```

## Observações

O valor verdadeiro da propriedade especifica o comportamento de retorno ao pai na apresentação de slides. 

Exemplo: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Ver também

* Classe [IZoomObject](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)