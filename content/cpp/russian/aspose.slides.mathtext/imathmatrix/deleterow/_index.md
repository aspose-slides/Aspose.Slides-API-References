---
title: DeleteRow()
second_title: Справочник API Aspose.Slides для C++
description: Удаляет указанную строку
type: docs
weight: 300
url: /ru/aspose.slides.mathtext/imathmatrix/deleterow/
---
## IMathMatrix::DeleteRow(int32_t) метод

Удаляет указанную строку

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteRow(int32_t rowIndex)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| rowIndex | **int32_t** | Нулевой индекс строки, которую нужно удалить. |
## Примечания



Пример: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## Смотрите также

* Класс [IMathMatrix](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)