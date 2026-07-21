---
title: set_ColumnGap()
second_title: Aspose.Slides для C++ справка по API
description: "Значение горизонтального расстояния между столбцами матрицы; Если ColumnGapRule установлен в 3 (\"Exactly\"), то единица измерения интерпретируется как twips (1/20 пункта) Если ColumnGapRule установлен в 4 (\"Multiple\"), то единица измерения интерпретируется как количество шагов 0,5 em. В остальных случаях игнорируется. По умолчанию: 0"
type: docs
weight: 144
url: /ru/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) метод


Значение горизонтального расстояния между столбцами матрицы; если ColumnGapRule установлен в 3 (\"Exactly\"), то единица измерения интерпретируется как twips (1/20 пункта) Если ColumnGapRule установлен в 4 (\"Multiple\"), то единица измерения интерпретируется как количество шагов 0.5 em. В остальных случаях игнорируется. По умолчанию: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
```

## Примечания


Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## См. также

* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)