---
title: get_Base()
second_title: Справочник API Aspose.Slides для C++
description: Базовый аргумент
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_base/
---
## MathLeftSubSuperscriptElement::get_Base() метод


Базовый аргумент

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Base() override
```

## Примечания


Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto baseElem = leftSubSuperscript->get_Base();
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathLeftSubSuperscriptElement](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)