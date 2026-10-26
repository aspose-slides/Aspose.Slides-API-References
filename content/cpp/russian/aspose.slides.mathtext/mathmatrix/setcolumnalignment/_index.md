---
title: SetColumnAlignment()
second_title: Справочник API Aspose.Slides для C++
description: Устанавливает горизонтальное выравнивание указанного столбца
type: docs
weight: 261
url: /ru/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) метод

Устанавливает горизонтальное выравнивание указанного столбца

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | **int32_t** | Нулевой индекс столбца |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Новое значение горизонтального выравнивания указанного столбца |
## Примечания



Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## См. также

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Класс [MathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)