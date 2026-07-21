---
title: get_ColumnGapRule()
second_title: Aspose.Slides для C++ справочник API
description: "Тип горизонтального промежутка между столбцами матрицы; единицы горизонтального промежутка могут быть ems или points (хранятся как twips). По умолчанию: SingleSpacingGap (0)"
type: docs
weight: 105
url: /ru/aspose.slides.mathtext/mathmatrix/get_columngaprule/
---
## MathMatrix::get_ColumnGapRule() метод


Тип горизонтального промежутка между столбцами матрицы; единицы горизонтального промежутка могут быть ems или points (хранятся как twips). По умолчанию: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_ColumnGapRule() override
```

## Примечания


Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## См. также

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)