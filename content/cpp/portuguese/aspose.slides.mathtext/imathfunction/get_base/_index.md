---
title: get_Base()
second_title: Referência da API Aspose.Slides for C++
description: Argumento da Função
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() método

Argumento da Função

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## Observações

Exemplo:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathFunction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)