---
title: get_Limit()
second_title: Referência da API Aspose.Slides para C++
description: Argumento de limite
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() método


Argumento de limite

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## Observações


Exemplo: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathLimit](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)