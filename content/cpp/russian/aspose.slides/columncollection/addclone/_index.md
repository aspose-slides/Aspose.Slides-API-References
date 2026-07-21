---
title: AddClone()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт копию указанной строки-шаблона и вставляет её в конец таблицы.
type: docs
weight: 53
url: /ru/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) метод


Создает копию указанной строки-шаблона и вставляет её в конец таблицы.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) используется в качестве шаблона. |
| withAttachedColumns | **bool** | True — также копировать все столбцы, присоединённые к строке-шаблону. |

### Возвращаемое значение

Добавленные столбцы.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IColumn](../../icolumn/)
* Класс [ColumnCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)