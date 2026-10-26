---
title: InsertClone()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie an der angegebenen Position in einer Tabelle ein.
type: docs
weight: 66
url: /de/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) Methode

Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie an der angegebenen Position in einer Tabelle ein.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Index einer neuen Zeile. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) wird als Vorlage verwendet. |
| withAttachedRows | **bool** | True, um ebenfalls alle an die Vorlagenzeile angehängten Zeilen zu kopieren. |

### Rückgabewert

Eingefügte Zeilen.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IRow](../../irow/)
* Klasse [RowCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)