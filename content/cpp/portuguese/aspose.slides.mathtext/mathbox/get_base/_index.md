---
title: get_Base()
second_title: Referência da API Aspose.Slides para C++
description: Argumento Base
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathbox/get_base/
---
## MathBox::get_Base() método


Argumento Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBox::get_Base() override
```

## Observações


Exemplo: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
auto baseArg = box->get_Base();
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBox](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)