---
title: InsertClone()
second_title: Aspose.Slides для C++ справочник API
description: Создает копию указанного шаблонного столбца и вставляет её в указанную позицию в таблице.
type: docs
weight: 66
url: /ru/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) метод

Создает копию указанного шаблонного столбца и вставляет её в указанную позицию таблицы.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс нового столбца. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) который используется как шаблон. |
| withAttachedColumns | **bool** | True, если нужно также скопировать все столбцы, присоединённые к шаблонному столбцу. |

### Возвращаемое значение

Вставленные столбцы.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumn](../../icolumn/)
* Class [ColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)