---
title: InsertClone()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en kopia av den angivna mallraden och infogar den på den angivna positionen i en tabell.
type: docs
weight: 27
url: /sv/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) method

Skapar en kopia av den angivna mallraden och infogar den på den angivna positionen i en tabell.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för en ny rad. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) som används som en mall. |
| withAttachedRows | **bool** | True för att även kopiera alla rader som är fästa vid mallraden. |

### Returvärde

Infogade rader.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IRow](../../irow/)
* Klass [IRowCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)