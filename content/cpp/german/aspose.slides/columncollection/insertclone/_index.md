---
title: InsertClone()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Kopie der angegebenen Vorlagen-Spalte und fügt sie an der angegebenen Position in einer Tabelle ein.
type: docs
weight: 66
url: /de/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) Methode


Erstellt eine Kopie der angegebenen Vorlage-Spalte und fügt sie an der angegebenen Position in einer Tabelle ein.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Index einer neuen Spalte. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) die als Vorlage verwendet wird. |
| withAttachedColumns | **bool** | True, um auch alle an die Vorlage-Spalte angehängten Spalten zu kopieren. |

### Rückgabewert

Eingefügte Spalten.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IColumn](../../icolumn/)
* Klasse [ColumnCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)