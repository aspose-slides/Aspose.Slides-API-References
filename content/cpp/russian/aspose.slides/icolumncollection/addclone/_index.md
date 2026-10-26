---
title: AddClone()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт копию указанной строки-шаблона и вставляет её в конец таблицы.
type: docs
weight: 14
url: /ru/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) метод

Создаёт копию указанной строки-шаблона и вставляет её в конец таблицы.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) используется в качестве шаблона. |
| withAttachedColumns | **bool** | True, если нужно также скопировать все столбцы, присоединённые к строке-шаблону. |

### Возвращаемое значение

Добавленные столбцы.

## См. также

* Тип-определение [ArrayPtr](../../../system/arrayptr/)
* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [IColumn](../../icolumn/)
* Класс [IColumnCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)