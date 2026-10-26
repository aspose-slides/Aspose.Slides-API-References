---
title: idx_get()
second_title: Aspose.Slides для справочника API C++
description: Элементы матрицы
type: docs
weight: 209
url: /ru/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) метод

Элементы матрицы

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| row | **int32_t** | Нулевой индекс строки для получения элемента |
| column | **int32_t** | Нулевой индекс столбца для получения элемента |

### Возвращаемое значение


## Примечания



Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)