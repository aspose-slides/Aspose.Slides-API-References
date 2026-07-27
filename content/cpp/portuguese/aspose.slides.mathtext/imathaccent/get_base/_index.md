---
title: get_Base()
second_title: Referência da API Aspose.Slides for C++
description: O argumento ao qual o acento foi aplicado
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() método


O argumento ao qual o acento foi aplicado

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
```

## Observações


Exemplo: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathAccent](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)