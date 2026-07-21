---
title: GetColumnAlignment()
second_title: Aspose.Slides для C++ справка по API
description: Получить горизонтальное выравнивание указанного столбца
type: docs
weight: 248
url: /ru/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) method


Получить горизонтальное выравнивание указанного столбца

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```


### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Индекс столбца, нумерация с нуля |

### Возвращаемое значение

Горизонтальное выравнивание указанного столбца
## Примечание



Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## См. также

* Перечисление [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Класс [MathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)