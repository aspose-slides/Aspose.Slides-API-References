---
title: get_Superscript()
second_title: Справочник API Aspose.Slides для C++
description: Надстрочный
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathsuperscriptelement/get_superscript/
---
## MathSuperscriptElement::get_Superscript() метод

Надстрочный

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSuperscriptElement::get_Superscript() override
```

## Примечание

Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto super = superscriptElement->get_Superscript();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathSuperscriptElement](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)