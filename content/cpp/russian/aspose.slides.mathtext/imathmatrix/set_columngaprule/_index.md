---
title: set_ColumnGapRule()
second_title: Aspose.Slides для C++ справка API
description: "Тип горизонтального интервала между столбцами матрицы; единицы горизонтального интервала могут быть ems или points (хранятся как twips). По умолчанию: SingleSpacingGap (0)"
type: docs
weight: 118
url: /ru/aspose.slides.mathtext/imathmatrix/set_columngaprule/
---
## IMathMatrix::set_ColumnGapRule(MathSpacingRules) метод


Тип горизонтального интервала между столбцами матрицы; единицы горизонтального интервала могут быть ems или points (хранятся как twips). По умолчанию: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGapRule(MathSpacingRules value)=0
```

## Примечание

Пример:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Смотрите также

* Enum [MathSpacingRules](../../mathspacingrules/)
* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)