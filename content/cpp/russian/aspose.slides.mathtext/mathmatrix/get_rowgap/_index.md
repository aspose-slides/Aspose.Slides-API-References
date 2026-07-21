---
title: get_RowGap()
second_title: Aspose.Slides для C++ API справочник
description: "Значение вертикального интервала между строками матрицы; Если RowGapRule установлен в 3 (\"Exactly\"), то единица измерения интерпретируется как twips (1/20 части пункта) Если RowGapRule установлен в 4 (\"Multiple\"), то единица измерения интерпретируется как half-lines. По умолчанию: 0"
type: docs
weight: 183
url: /ru/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() метод

Значение вертикального интервала между строками матрицы; Если RowGapRule установлен в 3 (\"Exactly\"), то единица измерения интерпретируется как twips (1/20th of a point) Если RowGapRule установлен в 4 (\"Multiple\"), то единица измерения интерпретируется как half-lines. По умолчанию: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
```

## Примечания

Пример:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## См. также

* Класс [MathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)