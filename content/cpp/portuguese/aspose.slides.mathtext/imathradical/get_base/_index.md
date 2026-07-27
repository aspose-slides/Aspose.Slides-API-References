---
title: get_Base()
second_title: Referência da API Aspose.Slides para C++
description: Argumento Base
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() método

Argumento Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## Observações


Exemplo: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // raiz cúbica
auto baseElem = radical->get_Base();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathRadical](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)