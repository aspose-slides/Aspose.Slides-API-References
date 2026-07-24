---
title: AddClone()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am unteren Rand einer Tabelle ein.
type: docs
weight: 53
url: /de/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) Methode


Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am unteren Rand einer Tabelle ein.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) die als Vorlage verwendet wird. |
| withAttachedColumns | **bool** | True, um ebenfalls alle an die Vorlagenzeile angehängten Spalten zu kopieren. |

### Rückgabewert

Hinzugefügte Spalten.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IColumn](../../icolumn/)
* Klasse [ColumnCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)