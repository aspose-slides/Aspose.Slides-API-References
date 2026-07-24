---
title: InsertTable()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Tabelle und fügt sie an dem angegebenen Index in die Shape-Collection ein.
type: docs
weight: 482
url: /de/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) Methode

Erstellt eine neue Tabelle und fügt sie an der angegebenen Position in die Shape-Collection ein.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem die Tabelle eingefügt werden soll. |
| x | **float** | Die X-Koordinate der Tabelle in Punkten. |
| y | **float** | Die Y-Koordinate der Tabelle in Punkten. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Ein Array von double-Werten, das die Breiten der Tabelle\\u2019s Spalten in Punkten darstellt. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Ein Array von double-Werten, das die Höhen der Tabelle\\u2019s Zeilen in Punkten darstellt. |

### Rückgabewert

Das neu erstellte [ITable](../../itable/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ITable](../../itable/)
* Klasse [ShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)