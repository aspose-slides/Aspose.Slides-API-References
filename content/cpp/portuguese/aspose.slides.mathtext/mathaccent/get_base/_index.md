---
title: get_Base()
second_title: Referência de API Aspose.Slides para C++
description: O argumento ao qual o acento foi aplicado
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() método

O argumento ao qual o acento foi aplicado

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## Observações

Exemplo:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMathElement](../../imathelement/)
* classe [MathAccent](../)
* namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)