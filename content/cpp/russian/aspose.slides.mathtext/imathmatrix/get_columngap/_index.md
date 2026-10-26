---
title: get_ColumnGap()
second_title: Aspose.Slides для C++ справочник API
description: "Значение горизонтального расстояния между столбцами матрицы; Если ColumnGapRule установлен в 3 (\"Exactly\"), то единица измерения считается твипами (1/20 пункта) Если ColumnGapRule установлен в 4 (\"Multiple\"), то единица измерения считается количеством шагов по 0,5 em. В остальных случаях игнорируется. По умолчанию: 0"
type: docs
weight: 131
url: /ru/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() метод


Значение горизонтального расстояния между столбцами матрицы; Если ColumnGapRule установлен в 3 (\"Exactly\"), то единица измеряется в твипах (1/20 пункта) Если ColumnGapRule установлен в 4 (\"Multiple\"), то единица измеряется как количество шагов по 0.5 em. В остальных случаях игнорируется. По умолчанию: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
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