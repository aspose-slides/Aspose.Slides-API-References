---
title: set_RowGapRule()
second_title: Справочник API Aspose.Slides для C++
description: "Тип вертикального интервала между строками матрицы; единицы вертикального интервала могут быть строками или пунктами (хранятся в виде twips). По умолчанию: SingleSpacingGap (0)"
type: docs
weight: 170
url: /ru/aspose.slides.mathtext/imathmatrix/set_rowgaprule/
---
## IMathMatrix::set_RowGapRule(MathSpacingRules) метод

Тип вертикального интервала между строками матрицы; единицы вертикального интервала могут быть строками или пунктами (хранятся в виде twips). По умолчанию: SingleSpacingGap (0)

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGapRule(MathSpacingRules value)=0
```

## Примечания

Пример:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## См. также

* Перечисление [MathSpacingRules](../../mathspacingrules/)
* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)