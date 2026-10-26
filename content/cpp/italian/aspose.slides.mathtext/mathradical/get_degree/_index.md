---
title: get_Degree()
second_title: Riferimento API di Aspose.Slides per C++
description: Degree argomento
type: docs
weight: 14
url: /it/aspose.slides.mathtext/mathradical/get_degree/
---
## MathRadical::get_Degree() metodo


Degree argomento

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Degree() override
```

## Osservazioni


Esempio: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto degreeElem = radical->get_Degree();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathRadical](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)