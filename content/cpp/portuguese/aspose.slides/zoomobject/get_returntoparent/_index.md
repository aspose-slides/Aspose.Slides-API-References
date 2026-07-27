---
title: get_ReturnToParent()
second_title: Referência da API Aspose.Slides para C++
description: "Obtém o comportamento de navegação na apresentação de slides. Leitura bool. Valor padrão: false"
type: docs
weight: 27
url: /pt/aspose.slides/zoomobject/get_returntoparent/
---
## ZoomObject::get_ReturnToParent() método

Obtém o comportamento de navegação na apresentação de slides. Leitura **bool**. Valor padrão: false

```cpp
bool Aspose::Slides::ZoomObject::get_ReturnToParent() override
```

## Observações

O valor verdadeiro da propriedade especifica o comportamento de retorno ao pai na apresentação de slides.

Exemplo: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Ver também

* Classe [ZoomObject](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)