---
title: InsertTable()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt eine neue Tabelle und fügt sie in die Shape-Collection an dem angegebenen Index ein.
type: docs
weight: 443
url: /de/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method


Erstellt eine neue Tabelle und fügt sie in die Shape-Collection an der angegebenen Position ein.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem die Tabelle eingefügt werden soll. |
| x | **float** | Die x-Koordinate der Tabelle in Punkten. |
| y | **float** | Die y-Koordinate der Tabelle in Punkten. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Ein Array von double, das die Breiten der Tabellenspalten in Punkten darstellt. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Ein Array von double, das die Höhen der Tabellenzeilen in Punkten darstellt. |

### Rückgabewert

Die neu erstellte [ITable](../../itable/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ITable](../../itable/)
* Klasse [IShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)