---
title: get_Superscript()
second_title: Aspose.Slides для C++ справочник API
description: Надстрочный
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/imathsuperscriptelement/get_superscript/
---
## IMathSuperscriptElement::get_Superscript() метод


Superscript

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSuperscriptElement::get_Superscript()=0
```

## Примечания


Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto super = superscriptElement->get_Superscript();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathSuperscriptElement](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)