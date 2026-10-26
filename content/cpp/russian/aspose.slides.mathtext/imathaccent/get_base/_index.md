---
title: get_Base()
second_title: Справочник API Aspose.Slides для C++
description: Аргумент, к которому был применён акцент
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() метод


Аргумент, к которому был применён акцент

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
```

## Примечания


Пример: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathAccent](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)