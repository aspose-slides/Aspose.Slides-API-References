---
title: set_RowGapRule()
second_title: Aspose.Slides для C++ справочник API
description: "Тип вертикального интервала между строками матрицы; единицы вертикального интервала могут быть строками или точками (хранятся в twips). По умолчанию: SingleSpacingGap (0)"
type: docs
weight: 170
url: /ru/aspose.slides.mathtext/mathmatrix/set_rowgaprule/
---
## MathMatrix::set_RowGapRule(MathSpacingRules) метод

Тип вертикального интервала между строками матрицы; единицы вертикального интервала могут быть строками или точками (хранятся в twips). По умолчанию: SingleSpacingGap (0)

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGapRule(MathSpacingRules value) override
```

## Примечания

Пример:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Смотрите также

* Перечисление [MathSpacingRules](../../mathspacingrules/)
* Класс [MathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)