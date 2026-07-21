---
title: get_Base()
second_title: Справочник API Aspose.Slides для C++
description: Аргумент Base
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/mathsubscriptelement/get_base/
---
## MathSubscriptElement::get_Base() method


Аргумент Base

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSubscriptElement::get_Base() override
```

## Замечания


Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto baseElem = subscriptElement->get_Base();
```

## См. также

* Определение типа [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathSubscriptElement](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)