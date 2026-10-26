---
title: set_MinColumnWidth()
second_title: Aspose.Slides для C++ — справочник API
description: "Минимальная ширина столбца в twips (1/20 пункта) Расстояние между колонками (также называемое \\u201CColumn Gap\\u201D или \\u201CGap Width\\u201D) добавляется к MinColumnWidth для определения общего расстояния между колонками матрицы (расстояние между одинаковыми краями разных колонок). По умолчанию: 0."
type: docs
weight: 92
url: /ru/aspose.slides.mathtext/imathmatrix/set_mincolumnwidth/
---
## IMathMatrix::set_MinColumnWidth(uint32_t) метод

Минимальная ширина столбца в twips (1/20 доли пункта). Расстояние между колонками (также называемое \\u201CColumn Gap\\u201D или \\u201CGap Width\\u201D) добавляется к MinColumnWidth для определения общего Matrix [Column](../../../aspose.slides/column/) Spacing (расстояние между одинаковыми краями разных колонок). По умолчанию: 0.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_MinColumnWidth(uint32_t value)=0
```

## Примечания

Пример:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## Смотрите также

* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)