---
title: InsertColumnAfter()
second_title: Aspose.Slides для C++ справочник API
description: Вставьте новый столбец после указанного. Изначально все элементы в новом столбце равны null.
type: docs
weight: 339
url: /ru/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) метод

Insert a new column after the specified one Initially all elements in the new column are null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | **int32_t** | Index of the column after which to insert a new one |
## Примечания



Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Смотрите также

* Класс [MathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)