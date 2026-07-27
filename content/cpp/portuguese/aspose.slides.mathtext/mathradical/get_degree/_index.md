---
title: get_Degree()
second_title: Referência da API Aspose.Slides para C++
description: Argumento Degree
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() método

Degree argumento

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## Observações

Exemplo: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathRadical](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)