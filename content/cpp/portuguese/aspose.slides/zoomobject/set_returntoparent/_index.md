---
title: set_ReturnToParent()
second_title: Referência da API Aspose.Slides para C++
description: "Define o comportamento de navegação na apresentação de slides. Escreva bool. Valor padrão: false"
type: docs
weight: 40
url: /pt/aspose.slides/zoomobject/set_returntoparent/
---
## ZoomObject::set_ReturnToParent(bool) método


Define o comportamento de navegação na apresentação de slides. Escreva **bool**. Valor padrão: false

```cpp
void Aspose::Slides::ZoomObject::set_ReturnToParent(bool value) override
```

## Observações


O valor verdadeiro da propriedade especifica o comportamento de navegação de retorno ao pai na apresentação de slides. 

Exemplo: 
```cpp
System::SharedPtr<IZoomFrame> zoomFrame = pres->get_Slides()->idx_get(0)->get_Shapes()->AddZoomFrame(150.0f, 20.0f, 50.0f, 50.0f, pres->get_Slides()->idx_get(1));
zoomFrame->set_ReturnToParent(true);
```

## Veja Também

* Classe [ZoomObject](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)