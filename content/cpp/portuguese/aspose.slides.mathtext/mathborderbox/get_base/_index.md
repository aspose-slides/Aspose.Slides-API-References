---
title: get_Base()
second_title: Referência da API Aspose.Slides para C++
description: Argumento Base
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathborderbox/get_base/
---
## MathBorderBox::get_Base() método


Argumento Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBorderBox::get_Base() override
```

## Observações


Exemplo: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = borderBox->get_Base();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBorderBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)