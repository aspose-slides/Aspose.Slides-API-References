---
title: InsertTable()
second_title: Aspose.Slides для C++ — справочник API
description: Создаёт новую таблицу и вставляет её в коллекцию фигур по указанному индексу.
type: docs
weight: 482
url: /ru/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) метод


Создаёт новую таблицу и вставляет её в коллекцию фигур по указанному индексу.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, по которому вставляется таблица. |
| x | **float** | Координата x таблицы, в пунктах. |
| y | **float** | Координата y таблицы, в пунктах. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Массив double, представляющий ширины столбцов таблицы\\u2019s, в пунктах. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Массив double, представляющий высоты строк таблицы\\u2019s, в пунктах. |

### Возвращаемое значение

Созданный [ITable](../../itable/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [ITable](../../itable/)
* Класс [ShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)