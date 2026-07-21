---
title: DeleteColumn()
second_title: Справочник API Aspose.Slides для C++
description: Удаляет указанный столбец
type: docs
weight: 339
url: /ru/aspose.slides.mathtext/imathmatrix/deletecolumn/
---
## IMathMatrix::DeleteColumn(int32_t) method

Удаляет указанный столбец

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteColumn(int32_t columnIndex)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | **int32_t** | Нулевой-базовый индекс столбца, который нужно удалить. |
## Примечания



Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## Смотрите также

* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)