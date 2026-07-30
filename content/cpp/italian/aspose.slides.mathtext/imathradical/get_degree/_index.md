---
title: get_Degree()
second_title: Riferimento API di Aspose.Slides per C++
description: Argomento Degree
type: docs
weight: 14
url: /it/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() metodo


Argomento Degree

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## Osservazioni


Esempio: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // radice cubica
auto degreeElem = radical->get_Degree();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathRadical](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)