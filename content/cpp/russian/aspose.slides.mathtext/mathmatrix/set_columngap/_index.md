---
title: set_ColumnGap()
second_title: Aspose.Slides для C++ справка по API
description: "Значение горизонтального расстояния между столбцами матрицы; Если ColumnGapRule установлен в 3 (\"Exactly\"), то единица измерения интерпретируется как твипы (1/20 точки) Если ColumnGapRule установлен в 4 (\"Multiple\"), то единица измерения интерпретируется как количество шагов по 0,5 em. Во всех остальных случаях игнорируется. По умолчанию: 0"
type: docs
weight: 144
url: /ru/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) метод


Значение горизонтального расстояния между столбцами матрицы; Если ColumnGapRule установлен в 3 ("Exactly"), то единица измерения интерпретируется как твипы (1/20 точки) Если ColumnGapRule установлен в 4 ("Multiple"), то единица измерения интерпретируется как количество шагов по 0,5 em. Во всех остальных случаях игнорируется. По умолчанию: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
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