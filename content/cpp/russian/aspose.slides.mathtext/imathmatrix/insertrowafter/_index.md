---
title: InsertRowAfter()
second_title: Справочник API Aspose.Slides для C++
description: Вставляет новую строку после указанной. Изначально все элементы в новой строке равны null.
type: docs
weight: 287
url: /ru/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) метод

Вставляет новую строку после указанной. Изначально все элементы в новой строке равны null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rowIndex | **int32_t** | Индекс строки, после которой нужно вставить новую |
## Примечания



Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## См. также

* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)