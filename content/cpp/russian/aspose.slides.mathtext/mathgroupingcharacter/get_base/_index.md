---
title: get_Base()
second_title: Aspose.Slides для C++ справки API
description: Базовый аргумент
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathgroupingcharacter/get_base/
---
## MathGroupingCharacter::get_Base() method


Базовый аргумент

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathGroupingCharacter::get_Base() override
```

## Примечания


Пример: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
auto baseArg = groupingCharacter->get_Base();
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathGroupingCharacter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)