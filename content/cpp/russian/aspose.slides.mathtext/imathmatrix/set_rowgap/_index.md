---
title: set_RowGap()
second_title: "Справочник API Aspose.Slides для C++"
description: "Значение вертикального расстояния между строками матрицы; если RowGapRule установлено в 3 (\"Exactly\"), то единица измерения трактуется как twips (1/20 пункта) Если RowGapRule установлено в 4 (\"Multiple\"), то единица измерения трактуется как полулинии. По умолчанию: 0"
type: docs
weight: 196
url: /ru/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) метод

Значение вертикального расстояния между строками матрицы; если RowGapRule установлено в 3 ("Exactly"), то единица измерения трактуется как twips (1/20 пункта). Если RowGapRule установлено в 4 ("Multiple"), то единица измерения трактуется как полулинии. По умолчанию: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
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
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)