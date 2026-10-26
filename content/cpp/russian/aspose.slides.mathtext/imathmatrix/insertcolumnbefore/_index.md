---
title: InsertColumnBefore()
second_title: Справочник API Aspose.Slides для C++
description: Вставить новый столбец перед указанным. Изначально все элементы в новом столбце равны null.
type: docs
weight: 313
url: /ru/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) метод


Вставить новый столбец перед указанным. Изначально все элементы в новом столбце равны null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | **int32_t** | Индекс столбца, перед которым следует вставить новый |
## Примечание



Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## См. также

* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)