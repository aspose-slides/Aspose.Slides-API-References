---
title: get_Base()
second_title: Справочник API Aspose.Slides для C++
description: Аргумент, к которому был применён акцент
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() метод


Аргумент, к которому применён акцент

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## Примечания


Пример:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## См. также

* typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathAccent](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)