---
title: get_Limit()
second_title: Referência da API Aspose.Slides para C++
description: Argumento de limite
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() método


Argumento de limite

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
```

## Observações


Exemplo: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathLimit](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)