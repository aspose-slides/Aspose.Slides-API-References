---
title: get_Base()
second_title: Riferimento API Aspose.Slides per C++
description: Argomento Base
type: docs
weight: 1
url: /it/aspose.slides.mathtext/imathbox/get_base/
---
## IMathBox::get_Base() metodo


Argomento Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBox::get_Base()=0
```

## Osservazioni


Esempio: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
auto baseArg = box->get_Base();
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathBox](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)