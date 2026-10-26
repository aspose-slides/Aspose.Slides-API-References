---
title: InsertClone()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт копию указанного шаблонного столбца и вставляет её в указанную позицию таблицы.
type: docs
weight: 27
url: /ru/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) метод

Создаёт копию указанного шаблонного столбца и вставляет её в указанную позицию таблицы.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Index of a new column. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) используется в качестве шаблона. |
| withAttachedColumns | **bool** | True, если нужно также копировать все столбцы, присоединённые к шаблонному столбцу. |

### Возвращаемое значение

Inserted columns.

## Смотрите также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IColumn](../../icolumn/)
* Класс [IColumnCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)