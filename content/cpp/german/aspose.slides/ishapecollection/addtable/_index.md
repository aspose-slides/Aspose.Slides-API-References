---
title: AddTable()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Tabelle und fügt sie am Ende der Shape-Sammlung hinzu.
type: docs
weight: 430
url: /de/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) Methode

Erstellt eine neue Tabelle und fügt sie am Ende der Shape-Sammlung hinzu.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | **float** | Die x-Koordinate der Tabelle in Punkten. |
| y | **float** | Die y-Koordinate der Tabelle in Punkten. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Ein Array von doubles, das die Breiten der Tabellenspalten in Punkten darstellt. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Ein Array von doubles, das die Höhen der Tabellenzeilen in Punkten darstellt. |

### Rückgabewert

Das neu erstellte [ITable](../../itable/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ITable](../../itable/)
* Klasse [IShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)