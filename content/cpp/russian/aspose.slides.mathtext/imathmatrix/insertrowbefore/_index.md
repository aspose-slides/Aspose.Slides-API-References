---
title: InsertRowBefore()
second_title: Aspose.Slides для C++ справочник API
description: Вставьте новую строку перед указанной. Изначально все элементы в новой строке null.
type: docs
weight: 274
url: /ru/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) method

Вставьте новую строку перед указанной. Изначально все элементы в новой строке равны null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rowIndex | **int32_t** | Индекс строки, перед которой нужно вставить новую |
## Примечания



Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## См. также

* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)