---
title: get_Base()
second_title: Referência da API Aspose.Slides para C++
description: Argumento base
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathbox/get_base/
---
## IMathBox::get_Base() method


Argumento base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBox::get_Base()=0
```

## Observações


Exemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
auto baseArg = box->get_Base();
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathBox](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)