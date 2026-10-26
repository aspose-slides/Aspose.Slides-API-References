---
title: get_Base()
second_title: Riferimento API di Aspose.Slides per C++
description: Argomento base
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathradical/get_base/
---
## MathRadical::get_Base() metodo


Base argomento

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Base() override
```

## Osservazioni


Esempio: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto baseElem = radical->get_Base();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathRadical](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)