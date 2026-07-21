---
title: GetColumnAlignment()
second_title: Aspose.Slides для C++ справочник API
description: Получить горизонтальное выравнивание указанного столбца
type: docs
weight: 235
url: /ru/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) method


Получить горизонтальное выравнивание указанного столбца

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | **int32_t** | Нумерация столбцов начинается с нуля |

### Возвращаемое значение

Горизонтальное выравнивание указанного столбца
## Примечания



Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## См. также

* Перечисление [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)