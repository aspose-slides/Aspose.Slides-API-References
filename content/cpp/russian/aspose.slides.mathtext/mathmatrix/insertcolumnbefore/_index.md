---
title: InsertColumnBefore()
second_title: Aspose.Slides для C++ справочник API
description: Вставить новый столбец перед указанным Изначально все элементы в новом столбце равны null.
type: docs
weight: 326
url: /ru/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) метод

Вставить новый столбец перед указанным. Изначально все элементы в новом столбце равны null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | **int32_t** | Индекс столбца, перед которым следует вставить новый |

## Примечания

Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## См. также

* Класс [MathMatrix](../)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)