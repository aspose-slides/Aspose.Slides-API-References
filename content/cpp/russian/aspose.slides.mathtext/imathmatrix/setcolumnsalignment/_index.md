---
title: SetColumnsAlignment()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает горизонтальное выравнивание указанных столбцов
type: docs
weight: 261
url: /ru/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) метод

Устанавливает горизонтальное выравнивание указанных столбцов

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | **int32_t** | Нулевой индекс первого столбца, для которого устанавливается выравнивание |
| columnsCount | **uint32_t** | Количество столбцов, для которых задаётся выравнивание |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Новое значение горизонтального выравнивания указанного столбца |
## Примечания

Пример:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## См. также

* Перечисление [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)