---
title: InsertTable()
second_title: Aspose.Slides C++ API-referencia
description: Új táblát hoz létre, és a shape collection-be a megadott indexnél szúrja be.
type: docs
weight: 443
url: /hu/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) metódus


Létrehoz egy új táblát, és a shape collection-be a megadott indexnél szúrja be.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nulla-alapú index, amelynél a táblát beszúrják. |
| x | **float** | A táblázat x-koordinátája pontban. |
| y | **float** | A táblázat y-koordinátája pontban. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Egy double típusú tömb, amely a táblázat oszlopainak szélességét, pontban, tartalmazza. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Egy double típusú tömb, amely a táblázat sorainak magasságát, pontban, tartalmazza. |

### Visszatérési érték

Az újonnan létrehozott [ITable](../../itable/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [ITable](../../itable/)
* Osztály [IShapeCollection](../)
* Névtere [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)