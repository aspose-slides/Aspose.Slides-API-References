---
title: get_UpperLimit()
second_title: Referência da API Aspose.Slides para C++
description: Especifica o limite superior ou inferior
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/imathlimit/get_upperlimit/
---
## IMMathLimit::get_UpperLimit() método

Especifica o limite superior ou inferior

```cpp
virtual bool Aspose::Slides::MathText::IMathLimit::get_UpperLimit()=0
```

## Observações

Exemplo:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Veja Também

* Classe [IMathLimit](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)