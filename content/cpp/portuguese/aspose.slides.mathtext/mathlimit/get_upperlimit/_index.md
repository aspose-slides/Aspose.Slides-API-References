---
title: get_UpperLimit()
second_title: Referência da API Aspose.Slides para C++
description: Especifica limite superior ou inferior
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/mathlimit/get_upperlimit/
---
## MathLimit::get_UpperLimit() método


Especifica limite superior ou inferior

```cpp
bool Aspose::Slides::MathText::MathLimit::get_UpperLimit() override
```

## Observações


Exemplo: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Veja Também

* Classe [MathLimit](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)