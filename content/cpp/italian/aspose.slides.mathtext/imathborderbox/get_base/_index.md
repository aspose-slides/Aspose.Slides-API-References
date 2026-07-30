---
title: get_Base()
second_title: Riferimento API di Aspose.Slides per C++
description: Argomento Base
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathborderbox/get_base/
---
## IMathBorderBox::get_Base() metodo


argomento Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBorderBox::get_Base()=0
```

## Osservazioni


Esempio: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
auto baseArg = borderBox->get_Base();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathBorderBox](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)