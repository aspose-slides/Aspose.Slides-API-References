---
title: SetColumnAlignment()
second_title: Aspose.Slides для C++ справочник API
description: Устанавливает горизонтальное выравнивание указанного столбца
type: docs
weight: 248
url: /ru/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) метод

Задает горизонтальное выравнивание указанного столбца

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| columnIndex | **int32_t** | Индекс столбца, начиная с нуля |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Новое значение горизонтального выравнивания указанного столбца |
## Примечания

Example: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## См. также

* Перечисление [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)