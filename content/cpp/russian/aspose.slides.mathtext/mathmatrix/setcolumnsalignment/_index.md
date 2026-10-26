---
title: SetColumnsAlignment()
second_title: Aspose.Slides для C++ — справка по API
description: Установить горизонтальное выравнивание указанных столбцов
type: docs
weight: 274
url: /ru/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) метод

Установить горизонтальное выравнивание указанных столбцов

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | **int32_t** | Индекс первого столбца (нумерация с нуля), выравнивание которого нужно установить |
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
* Класс [MathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)