---
title: DeleteRow()
second_title: Aspose.Slides для C++ Справочник API
description: Удаляет указанную строку
type: docs
weight: 313
url: /ru/aspose.slides.mathtext/mathmatrix/deleterow/
---
## MathMatrix::DeleteRow(int32_t) метод

Удаляет указанную строку

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteRow(int32_t rowIndex) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| rowIndex | **int32_t** | Нулевой индекс строки, которую необходимо удалить. |
## Примечания



Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## Смотрите также

* Класс [MathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)