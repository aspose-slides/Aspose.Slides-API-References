---
title: AddTable()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новую таблицу и добавляет её в конец коллекции фигур.
type: docs
weight: 430
url: /ru/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) метод

Создаёт новую таблицу и добавляет её в конец коллекции фигур.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | Координата x таблицы в пунктах. |
| y | **float** | Координата y таблицы в пунктах. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Массив double, представляющий ширины столбцов таблицы, в пунктах. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Массив double, представляющий высоты строк таблицы, в пунктах. |

### Возвращаемое значение

Новый созданный [ITable](../../itable/).

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [ITable](../../itable/)
* Класс [IShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)