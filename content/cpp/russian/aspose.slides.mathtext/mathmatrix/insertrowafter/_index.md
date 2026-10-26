---
title: InsertRowAfter()
second_title: Справочник API Aspose.Slides для C++
description: Вставить новую строку после указанной. Изначально все элементы в новой строке имеют значение null.
type: docs
weight: 300
url: /ru/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) метод

Вставить новую строку после указанной. Изначально все элементы в новой строке имеют значение null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| rowIndex | **int32_t** | Индекс строки, после которой следует вставить новую |
## Примечания

Пример:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## См. также

* Класс [MathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)