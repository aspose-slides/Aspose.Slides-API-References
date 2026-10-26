---
title: get_Base()
second_title: Aspose.Slides para C++ - Referência da API
description: Argumento Base
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathlimit/get_base/
---
## MathLimit::get_Base() método

Argumento Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Base() override
```

## Observações

Exemplo:
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## Veja Também

* Classe [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathLimit](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)