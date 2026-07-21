---
title: get_RowGapRule()
second_title: Справочник API Aspose.Slides для C++
description: "Тип вертикального интервала между строками матрицы; единицы вертикального интервала могут быть строками или пунктами (хранятся как twips). По умолчанию: SingleSpacingGap (0)"
type: docs
weight: 157
url: /ru/aspose.slides.mathtext/mathmatrix/get_rowgaprule/
---
## MathMatrix::get_RowGapRule() метод

Тип вертикального интервала между строками матрицы; единицы вертикального интервала могут быть строками или пунктами (хранятся как twips). По умолчанию: SingleSpacingGap (0)

```cpp
MathSpacingRules Aspose::Slides::MathText::MathMatrix::get_RowGapRule() override
```

## Примечание

Пример:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## См. также

* Перечисление [MathSpacingRules](../../mathspacingrules/)
* Класс [MathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)