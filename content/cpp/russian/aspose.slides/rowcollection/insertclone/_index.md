---
title: InsertClone()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт копию указанной шаблонной строки и вставляет её в указанную позицию в таблице.
type: docs
weight: 66
url: /ru/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) метод

Создаёт копию указанной шаблонной строки и вставляет её в указанную позицию в таблице.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс новой строки. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) который используется как шаблон. |
| withAttachedRows | **bool** | True, если также копировать все строки, прикреплённые к шаблонной строке. |

### Значение возврата

Вставленные строки.

## См. также

* Тип-определение [ArrayPtr](../../../system/arrayptr/)
* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [IRow](../../irow/)
* Класс [RowCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)