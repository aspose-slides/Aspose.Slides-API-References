---
title: get_Subscript()
second_title: Aspose.Slides для C++ справочник API
description: Подстрочный
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/imathsubscriptelement/get_subscript/
---
## IMathSubscriptElement::get_Subscript() метод

Subscript

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSubscriptElement::get_Subscript()=0
```

## Примечания

Пример:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto sub = subscriptElement->get_Subscript();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathSubscriptElement](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)