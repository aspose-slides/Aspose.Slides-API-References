---
title: get_Base()
second_title: Referência da API Aspose.Slides para C++
description: Argumento da Função
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() método

Argumento da Função

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## Observações

Exemplo: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathFunction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)