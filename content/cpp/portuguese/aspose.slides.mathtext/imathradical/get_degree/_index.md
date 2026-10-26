---
title: get_Degree()
second_title: Referência da API Aspose.Slides para C++
description: Argumento Degree
type: docs
weight: 14
url: /pt/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() método

Argumento Degree

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## Observações

Exemplo: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // raiz cúbica
auto degreeElem = radical->get_Degree();
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathRadical](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)