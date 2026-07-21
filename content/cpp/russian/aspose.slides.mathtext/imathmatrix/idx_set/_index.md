---
title: idx_set()
second_title: Справочник API Aspose.Slides для C++
description: Элементы матрицы
type: docs
weight: 222
url: /ru/aspose.slides.mathtext/imathmatrix/idx_set/
---
## IMathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) method


Элементы матрицы

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| row | **int32_t** | Нулевой индекс строки для получения элемента |
| column | **int32_t** | Нулевой индекс столбца для получения элемента |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
## Примечания



Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathMatrix](../)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)