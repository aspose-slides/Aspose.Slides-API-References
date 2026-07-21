---
title: AddClone()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт копию указанной шаблонной строки и вставляет её в конец таблицы.
type: docs
weight: 53
url: /ru/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) метод

Создает копию указанной шаблонной строки и вставляет её в конец таблицы.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) который используется как шаблон. |
| withAttachedRows | **bool** | True, если также копировать все строки, прикрепленные к шаблонной строке. |

### Возвращаемое значение

Добавленные строки.

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IRow](../../irow/)
* Класс [RowCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)