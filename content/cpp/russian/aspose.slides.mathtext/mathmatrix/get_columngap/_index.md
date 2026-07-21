---
title: get_ColumnGap()
second_title: Справочник API Aspose.Slides для C++
description: "Значение горизонтального расстояния между колонками матрицы; если ColumnGapRule установлен в 3 (\"Exactly\"), то единица измерения интерпретируется как twips (1/20 пункта) если ColumnGapRule установлен в 4 (\"Multiple\"), то единица измеряется как количество шагов по 0,5 em. В остальных случаях игнорируется. По умолчанию: 0"
type: docs
weight: 131
url: /ru/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() метод

Значение горизонтального расстояния между колонками матрицы; Если ColumnGapRule установлен в 3 ("Exactly"), то единица измерения интерпретируется как twips (1/20 части пункта). Если ColumnGapRule установлен в 4 ("Multiple"), то единица измеряется как количество шагов по 0,5 em. В остальных случаях игнорируется. По умолчанию: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## Примечания

Пример:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## См. также

* Класс [MathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)