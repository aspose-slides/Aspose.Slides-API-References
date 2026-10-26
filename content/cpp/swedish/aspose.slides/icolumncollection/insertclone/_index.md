---
title: InsertClone()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en kopia av den specificerade mallkolumnen och infogar den på den angivna positionen i en tabell.
type: docs
weight: 27
url: /sv/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) metod


Skapar en kopia av den specificerade mallkolumnen och inför den på den angivna positionen i en tabell.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för en ny kolumn. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) som används som mall. |
| withAttachedColumns | **bool** | True för att även kopiera alla kolumner som är fästa vid mallkolumnen. |

### Returvärde

Infogade kolumner.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IColumn](../../icolumn/)
* Klass [IColumnCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)