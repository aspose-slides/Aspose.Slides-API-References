---
title: AddClone()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт копию указанной шаблонной строки и вставляет её в конец таблицы.
type: docs
weight: 14
url: /ru/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) метод

Создаёт копию указанной шаблонной строки и вставляет её в конец таблицы.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) используется в качестве шаблона. |
| withAttachedRows | **bool** | True, если также копировать все строки, присоединённые к шаблонной строке. |

### Возвращаемое значение

Добавленные строки.

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IRow](../../irow/)
* Класс [IRowCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)