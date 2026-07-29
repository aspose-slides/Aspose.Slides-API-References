---
title: AddClone()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en kopia av den angivna mallraden och infogar den längst ner i en tabell.
type: docs
weight: 14
url: /sv/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) method

Skapar en kopia av den angivna mallraden och infogar den längst ner i en tabell.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) som används som mall. |
| withAttachedColumns | **bool** | True för att även kopiera alla kolumner som är fästa vid mallraden. |

### Returvärde

Tillagda kolumner.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IColumn](../../icolumn/)
* Klass [IColumnCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)