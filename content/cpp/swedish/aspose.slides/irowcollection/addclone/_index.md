---
title: AddClone()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en kopia av den angivna mallraden och infogar den längst ner i en tabell.
type: docs
weight: 14
url: /sv/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) metod


Skapar en kopia av den angivna mallraden och infogar den längst ner i en tabell.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) som används som en mall. |
| withAttachedRows | **bool** | True för att även kopiera alla rader som är bifogade till mallraden. |

### Returvärde

Tillagda rader.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IRow](../../irow/)
* Klass [IRowCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)