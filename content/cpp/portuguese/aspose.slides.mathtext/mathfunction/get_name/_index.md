---
title: get_Name()
second_title: Referência da API Aspose.Slides para C++
description: Nome da função Por exemplo, nomes de funções são sin e cos
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() método

Nome da função Por exemplo, nomes de funções são sin e cos

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## Observações

Exemplo: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathFunction](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)