---
title: get_RowGap()
second_title: Справочник API Aspose.Slides for C++
description: "Значение вертикального расстояния между строками матрицы; Если RowGapRule установлен в 3 (\"Exactly\"), то единица измеряется в твипах (1/20 пункта) Если RowGapRule установлен в 4 (\"Multiple\"), то единица измеряется в полустроках. По умолчанию: 0"
type: docs
weight: 183
url: /ru/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() метод

Значение вертикального расстояния между строками матрицы; Если RowGapRule установлен в 3 ("Exactly"), то единица измеряется в твипах (1/20 пункта) Если RowGapRule установлен в 4 ("Multiple"), то единица измеряется в полустроках. По умолчанию: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
```

## Примечания

Пример:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## См. также

* Класс [IMathMatrix](../)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)