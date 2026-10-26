---
title: InsertColumnAfter()
second_title: Aspose.Slides для C++ справочник API
description: Вставьте новый столбец после указанного. Изначально все элементы в новом столбце равны null.
type: docs
weight: 326
url: /ru/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) метод

Вставьте новый столбец после указанного. Изначально все элементы в новом столбце равны null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | **int32_t** | Индекс столбца, после которого следует вставить новый |
## Примечания

Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Смотрите также

* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)