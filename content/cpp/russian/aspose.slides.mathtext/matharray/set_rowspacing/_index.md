---
title: set_RowSpacing()
second_title: Справка API Aspose.Slides для C++
description: "Расстояние между строками массива. Используется только когда RowSpacingRule установлен в 3 Exact, в этом случае единица измерения — пункты, или Multiple, в этом случае единица измерения — полустроки. По умолчанию: 0"
type: docs
weight: 131
url: /ru/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) method

Расстояние между строками массива. Используется только когда RowSpacingRule установлен в 3 Exact, в этом случае единица измерения — пункты, или Multiple, в этом случае единица измерения — полустроки. По умолчанию: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
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