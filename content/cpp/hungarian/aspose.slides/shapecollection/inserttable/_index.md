---
title: InsertTable()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehoz egy új táblázatot, és beilleszti a shape collection-be a megadott indexnél.
type: docs
weight: 482
url: /hu/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) metódus

Létrehoz egy új táblázatot, és beilleszti a shape collection-be a megadott indexnél.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nulla-alapú index, amelynél a táblázatot be kell szúrni. |
| x | **float** | A táblázat x-koordinátája pontokban. |
| y | **float** | A táblázat y-koordinátája pontokban. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | A double típusú tömb, amely a táblázat oszlopainak szélességét tartalmazza pontokban. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | A double típusú tömb, amely a táblázat sorainak magasságát tartalmazza pontokban. |

### Visszatérési érték

Az újonnan létrehozott [ITable](../../itable/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [ITable](../../itable/)
* Osztály [ShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)