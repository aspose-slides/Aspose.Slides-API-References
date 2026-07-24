---
title: InsertClone()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Kopie der angegebenen Vorlagen-Spalte und fügt sie an der angegebenen Position in einer Tabelle ein.
type: docs
weight: 27
url: /de/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) method

Erstellt eine Kopie der angegebenen Vorlagen-Spalte und fügt sie an der angegebenen Position in einer Tabelle ein.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Index einer neuen Spalte. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) die als Vorlage verwendet wird. |
| withAttachedColumns | **bool** | Wahr, um ebenfalls alle an die Vorlagen-Spalte angehängten Spalten zu kopieren. |

### Rückgabewert

Eingefügte Spalten.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IColumn](../../icolumn/)
* Klasse [IColumnCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)