---
title: AddClone()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am Ende einer Tabelle ein.
type: docs
weight: 53
url: /de/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) Methode

Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am Ende einer Tabelle ein.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) die als Vorlage verwendet wird. |
| withAttachedRows | **bool** | Wahr, um ebenfalls alle an die Vorlagenzeile angehängten Zeilen zu kopieren. |

### Rückgabewert

Hinzugefügte Zeilen.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IRow](../../irow/)
* Klasse [RowCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)