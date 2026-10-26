---
title: InsertClone()
second_title: Справочник API Aspose.Slides для C++
description: Создает копию указанной шаблонной строки и вставляет её в указанную позицию в таблице.
type: docs
weight: 27
url: /ru/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) метод


Создает копию указанной шаблонной строки и вставляет её в указанную позицию в таблице.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Индекс новой строки. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) который используется как шаблон. |
| withAttachedRows | **bool** | True, если также копировать все строки, прикреплённые к шаблонной строке. |

### Возвращаемое значение

Вставленные строки.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IRow](../../irow/)
* Класс [IRowCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)