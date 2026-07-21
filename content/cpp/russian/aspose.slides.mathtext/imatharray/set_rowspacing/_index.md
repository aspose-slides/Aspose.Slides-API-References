---
title: set_RowSpacing()
second_title: Aspose.Slides для C++ справочник API
description: "Расстояние между строками массива. Используется только когда RowSpacingRule установлен в 3 Exactly, в этом случае единица измерения — точки, или Multiple, в этом случае единица измерения — полулинии. По умолчанию: 0"
type: docs
weight: 131
url: /ru/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) метод

Расстояние между строками массива. Используется только когда RowSpacingRule установлен в 3 Exactly, в этом случае единица измерения — точки, или Multiple, в этом случае единица измерения — полулиний. По умолчанию: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## Примечания


Пример: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Смотрите также

* Класс [IMathArray](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)