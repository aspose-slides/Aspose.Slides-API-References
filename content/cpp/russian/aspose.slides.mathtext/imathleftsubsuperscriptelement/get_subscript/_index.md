---
title: get_Subscript()
second_title: Aspose.Slides для C++ справочник API
description: Нижний индекс
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/imathleftsubsuperscriptelement/get_subscript/
---
## IMathLeftSubSuperscriptElement::get_Subscript() метод


Нижний индекс

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLeftSubSuperscriptElement::get_Subscript()=0
```

## Примечания


Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = leftSubSuperscript->get_Subscript();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathLeftSubSuperscriptElement](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)