---
title: AddTable()
second_title: Aspose.Slides C++ API referencia
description: Új táblát hoz létre, és a shape collection végéhez adja hozzá.
type: docs
weight: 430
url: /hu/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) method


Létrehoz egy új táblát, és hozzáadja a alakzatgyűjtemény végéhez.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | A tábla x-koordinátája pontban. |
| y | **float** | A tábla y-koordinátája pontban. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Egy double típusú tömb, amely a tábla oszlopainak szélességét tartalmazza, pontban. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Egy double típusú tömb, amely a tábla sorainak magasságát tartalmazza, pontban. |

### Visszatérési érték

Az újonnan létrehozott [ITable](../../itable/).

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Típusdefiníció [ArrayPtr](../../../system/arrayptr/)
* Osztály [ITable](../../itable/)
* Osztály [IShapeCollection](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)