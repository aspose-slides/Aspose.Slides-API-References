---
title: MathSubscriptElement()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый экземпляр класса MathSubscriptElement.
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/mathsubscriptelement/mathsubscriptelement/
---
## MathSubscriptElement::MathSubscriptElement(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) конструктор

Инициализирует новый экземпляр класса [MathSubscriptElement](../).

```cpp
Aspose::Slides::MathText::MathSubscriptElement::MathSubscriptElement(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> subScript)
```

## Примечания

Пример:
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"X");
System::SharedPtr<IMathElement> subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathSubscriptElement](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)