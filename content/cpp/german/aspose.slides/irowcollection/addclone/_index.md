---
title: AddClone()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am Ende einer Tabelle ein.
type: docs
weight: 14
url: /de/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) Methode


Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am Ende einer Tabelle ein.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) die als Vorlage verwendet wird. |
| withAttachedRows | **bool** | True, um auch alle an die Vorlagenzeile angehängten Zeilen zu kopieren. |

### Rückgabewert

Hinzugefügte Zeilen.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IRow](../../irow/)
* Klasse [IRowCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)