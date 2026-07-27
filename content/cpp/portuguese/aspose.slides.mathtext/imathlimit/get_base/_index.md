---
title: get_Base()
second_title: Referência da API Aspose.Slides para C++
description: Argumento Base
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathlimit/get_base/
---
## IMathLimit::get_Base() método

Argumento Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Base()=0
```

## Observações

Exemplo: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathLimit](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)