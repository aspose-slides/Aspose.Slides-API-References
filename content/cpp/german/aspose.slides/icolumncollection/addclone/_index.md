---
title: AddClone()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am Ende einer Tabelle ein.
type: docs
weight: 14
url: /de/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) Methode

Erstellt eine Kopie der angegebenen Vorlagenzeile und fügt sie am Ende einer Tabelle ein.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) die als Vorlage verwendet wird. |
| withAttachedColumns | **bool** | True, um auch alle an die Vorlagenzeile angehängten Spalten zu kopieren. |

### Rückgabewert

Hinzugefügte Spalten.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IColumn](../../icolumn/)
* Klasse [IColumnCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)