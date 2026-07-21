---
title: InsertRowBefore()
second_title: Aspose.Slides для C++ справочник API
description: Вставьте новую строку перед указанной. Изначально все элементы в новой строке имеют значение null.
type: docs
weight: 287
url: /ru/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) метод

Insert a new row before the specified one Initially all elements in the new row are null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| rowIndex | **int32_t** | Индекс строки, перед которой следует вставить новую |

## Замечания



Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## См. также

* Класс [MathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)