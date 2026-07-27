---
title: get_Base()
second_title: Referência da API Aspose.Slides para C++
description: Argumento Base
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathradical/get_base/
---
## MathRadical::get_Base() método


Argumento Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Base() override
```

## Observações


Exemplo: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto baseElem = radical->get_Base();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathRadical](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)