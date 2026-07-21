---
title: set_RowGap()
second_title: Aspose.Slides для C++ справочник API
description: "Значение вертикального расстояния между строками матрицы; если RowGapRule установлен в 3 (\"Exactly\"), то единица измерения интерпретируется как twips (1/20 точки) Если RowGapRule установлен в 4 (\"Multiple\"), то единица измерения интерпретируется как полулинии. По умолчанию: 0"
type: docs
weight: 196
url: /ru/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) метод

Значение вертикального расстояния между строками матрицы; если RowGapRule установлен в 3 ("Exactly"), то единица измерения интерпретируется как twips (1/20 точки). Если RowGapRule установлен в 4 ("Multiple"), то единица измерения интерпретируется как полулинии. По умолчанию: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
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