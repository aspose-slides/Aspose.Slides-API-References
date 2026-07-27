---
title: set_UpperLimit()
second_title: Referência da API Aspose.Slides para C++
description: Especifica limite superior ou inferior
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/imathlimit/set_upperlimit/
---
## IMathLimit::set_UpperLimit(bool) method


Especifica limite superior ou inferior

```cpp
virtual void Aspose::Slides::MathText::IMathLimit::set_UpperLimit(bool value)=0
```

## Observações


Exemplo: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
limitElement->set_UpperLimit(false);
```

## Veja Também

* Classe [IMathLimit](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)