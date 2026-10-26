---
title: get_RowSpacing()
second_title: Справочник API Aspose.Slides для C++
description: "Расстояние между строками массива. Используется только когда RowSpacingRule установлен в 3 Exactly, в этом случае единицей измерения являются точки, или Multiple, в котором единицей измерения являются полустроки. По умолчанию: 0"
type: docs
weight: 118
url: /ru/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() метод

Расстояние между строками массива. Используется только когда RowSpacingRule установлен в 3 Exactly, в этом случае единицей измерения являются точки, или Multiple, в котором единицей измерения являются полустроки. По умолчанию: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## Примечания

Пример:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## См. также

* Класс [MathArray](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)