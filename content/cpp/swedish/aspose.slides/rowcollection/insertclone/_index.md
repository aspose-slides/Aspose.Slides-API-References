---
title: InsertClone()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en kopia av den specificerade mallraden och infogar den på den specificerade positionen i en tabell.
type: docs
weight: 66
url: /sv/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) metod

Skapar en kopia av den specificerade mallraden och infogar den på den specificerade positionen i en tabell.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för en ny rad. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) som används som en mall. |
| withAttachedRows | **bool** | True för att även kopiera alla rader som är kopplade till mallraden. |

### Returvärde

Infogade rader.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IRow](../../irow/)
* Klass [RowCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)