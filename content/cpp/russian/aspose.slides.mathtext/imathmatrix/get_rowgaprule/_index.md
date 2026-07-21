---
title: get_RowGapRule()
second_title: Aspose.Slides для C++ справка API
description: "Тип вертикального отступа между строками матрицы; единицы вертикального отступа могут быть строками или пунктами (хранятся в твипс). По умолчанию: SingleSpacingGap (0)"
type: docs
weight: 157
url: /ru/aspose.slides.mathtext/imathmatrix/get_rowgaprule/
---
## IMathMatrix::get_RowGapRule() method


Тип вертикального отступа между строками матрицы; вертикальные единицы отступа могут быть строками или пунктами (хранятся в твипс). По умолчанию: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_RowGapRule()=0
```

## Примечания


Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## См. также

* Enum [MathSpacingRules](../../mathspacingrules/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)