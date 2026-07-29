---
title: AddClone()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en kopia av den angivna mallraden och infogar den längst ner i en tabell.
type: docs
weight: 53
url: /sv/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) metod

Skapar en kopia av den angivna mallraden och infogar den längst ner i en tabell.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) som används som mall. |
| withAttachedColumns | **bool** | True för att även kopiera alla kolumner som är bifogade till mallraden. |

### Returvärde

Tillagda kolumner.

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IColumn](../../icolumn/)
* Klass [ColumnCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)