---
title: get_Base()
second_title: Aspose.Slides para C++ Referência de API
description: Argumento Base
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathborderbox/get_base/
---
## IMathBorderBox::get_Base() método

Argumento Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBorderBox::get_Base()=0
```

## Observações


Exemplo: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
auto baseArg = borderBox->get_Base();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathBorderBox](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)