---
title: InsertClone()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en kopia av den angivna mallkolumnen och infogar den på den angivna positionen i en tabell.
type: docs
weight: 66
url: /sv/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) metod


Skapar en kopia av den angivna mallkolumnen och infogar den på den angivna positionen i en tabell.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för en ny kolumn. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) som används som mall. |
| withAttachedColumns | **bool** | True för att även kopiera alla kolumner som är kopplade till mallkolumnen. |

### Returvärde

Infogade kolumner.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IColumn](../../icolumn/)
* Klass [ColumnCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)