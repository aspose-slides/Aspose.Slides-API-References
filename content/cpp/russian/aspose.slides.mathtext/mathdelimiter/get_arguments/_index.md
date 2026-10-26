---
title: get_Arguments()
second_title: Справочник API Aspose.Slides для C++
description: Один или несколько математических элементов, разделённых символами-разделителями
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathdelimiter/get_arguments/
---
## MathDelimiter::get_Arguments() метод

Один или несколько математических элементов, разделённых символами-разделителями

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathDelimiter::get_Arguments() override
```

## Примечания

Пример:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElementCollection](../../imathelementcollection/)
* Класс [MathDelimiter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)