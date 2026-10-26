---
title: DeleteColumn()
second_title: Aspose.Slides для C++ справочник API
description: Удаляет указанный столбец
type: docs
weight: 352
url: /ru/aspose.slides.mathtext/mathmatrix/deletecolumn/
---
## MathMatrix::DeleteColumn(int32_t) метод

Удаляет указанный столбец

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteColumn(int32_t columnIndex) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | **int32_t** | Нулевой индекс столбца, который нужно удалить. |
## Замечания

Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## См. также

* Класс [MathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)