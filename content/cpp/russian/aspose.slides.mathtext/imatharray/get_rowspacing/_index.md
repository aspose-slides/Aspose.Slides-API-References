---
title: get_RowSpacing()
second_title: Справочник API Aspose.Slides для C++
description: "Отступы между строками массива Используется только когда RowSpacingRule установлен в 3 Exactly, в этом случае единицей измерения являются пункты, или Multiple, в этом случае единицей измерения являются полуподстроки. По умолчанию: 0"
type: docs
weight: 118
url: /ru/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() метод


Отступы между строками массива Он используется только когда RowSpacingRule установлен в 3 Exactly, в этом случае единицей измерения являются пункты, или Multiple, в этом случае единицей измерения являются полуподстроки. По умолчанию: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
```

## Примечания


Пример: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## См. также

* Класс [IMathArray](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)