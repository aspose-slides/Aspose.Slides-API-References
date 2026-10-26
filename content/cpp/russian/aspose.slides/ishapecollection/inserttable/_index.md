---
title: InsertTable()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новую таблицу и вставляет её в коллекцию фигур по указанному индексу.
type: docs
weight: 443
url: /ru/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method

Создаёт новую таблицу и вставляет её в коллекцию фигур по указанному индексу.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, по которому вставляется таблица. |
| x | **float** | Координата x таблицы в пунктах. |
| y | **float** | Координата y таблицы в пунктах. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Массив double, представляющий ширины столбцов таблицы\\u2019s, в пунктах. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Массив double, представляющий высоты строк таблицы\\u2019s, в пунктах. |

### Возвращаемое значение

Созданный [ITable](../../itable/).

## См. также

* typedef [SharedPtr](../../../system/sharedptr/)
* typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [ITable](../../itable/)
* Класс [IShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)