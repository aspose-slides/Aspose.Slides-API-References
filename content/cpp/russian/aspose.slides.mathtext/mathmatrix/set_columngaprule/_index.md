---
title: set_ColumnGapRule()
second_title: Справочник API Aspose.Slides для C++
description: "Тип горизонтального интервала между столбцами матрицы; единицы горизонтального интервала могут быть ems или points (хранятся как twips). По умолчанию: SingleSpacingGap (0)"
type: docs
weight: 118
url: /ru/aspose.slides.mathtext/mathmatrix/set_columngaprule/
---
## MathMatrix::set_ColumnGapRule(MathSpacingRules) метод


Тип горизонтального расстояния между столбцами матрицы; единицы горизонтального расстояния могут быть ems или points (хранятся как twips). По умолчанию: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGapRule(MathSpacingRules value) override
```

## Примечания


Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## См. также

* Перечисление [MathSpacingRules](../../mathspacingrules/)
* Класс [MathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)