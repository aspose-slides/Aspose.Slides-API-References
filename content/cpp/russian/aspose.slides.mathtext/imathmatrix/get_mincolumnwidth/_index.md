---
title: get_MinColumnWidth()
second_title: Aspose.Slides для C++ справка API
description: "Минимальная ширина столбца в твипах (1/20 пункта) Расстояние между столбцами (также называется \\u201CColumn Gap\\u201D или \\u201CGap Width\\u201D) добавляется к MinColumnWidth для определения общего расстояния между столбцами матрицы (расстояние между одинаковыми краями разных столбцов). По умолчанию: 0."
type: docs
weight: 79
url: /ru/aspose.slides.mathtext/imathmatrix/get_mincolumnwidth/
---
## IMathMatrix::get_MinColumnWidth() method

Минимальная ширина столбца в твипах (1/20 части пункта) Расстояние между столбцами (также именуемое “Column Gap” или “Gap Width”) добавляется к MinColumnWidth для определения общего Matrix [Column](../../../aspose.slides/column/) Spacing (расстояние между одинаковыми краями разных столбцов). По умолчанию: 0.

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_MinColumnWidth()=0
```

## Примечания

Пример:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## См. также

* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)