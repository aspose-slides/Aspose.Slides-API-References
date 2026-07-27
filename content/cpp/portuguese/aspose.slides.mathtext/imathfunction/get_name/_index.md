---
title: get_Name()
second_title: Aspose.Slides para C++ Referência da API
description: Nome da função Por exemplo, os nomes de função são sin e cos
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() método

Nome da função Por exemplo, os nomes de função são sin e cos

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## Observações

Exemplo: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathFunction](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)