---
title: get_ColumnGapRule()
second_title: Справочник API Aspose.Slides для C++
description: "Тип горизонтального интервала между столбцами матрицы; единицы горизонтального интервала могут быть ems или points (хранятся как twips). По умолчанию: SingleSpacingGap (0)"
type: docs
weight: 105
url: /ru/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() метод

Тип горизонтального интервала между столбцами матрицы; единицы горизонтального интервала могут быть ems или points (хранятся как twips). По умолчанию: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## Примечания

Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Смотрите также

* Перечисление [MathSpacingRules](../../mathspacingrules/)
* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)