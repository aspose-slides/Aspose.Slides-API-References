---
title: InsertTable()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuwe tabel aan en voegt deze in de shape-collectie in op de opgegeven index.
type: docs
weight: 443
url: /nl/aspose.slides/ishapecollection/inserttable/
---
## IShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) methode


Creates a new table and inserts it into the shape collection at the specified index.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop de tabel moet worden ingevoegd. |
| x | **float** | De x-coördinaat van de tabel, in punten. |
| y | **float** | De y-coördinaat van de tabel, in punten. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Een array van doubles die de breedtes van de kolommen van de tabel weergeeft, in punten. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Een array van doubles die de hoogtes van de rijen van de tabel weergeeft, in punten. |

### Retourwaarde

De nieuw aangemaakte [ITable](../../itable/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ITable](../../itable/)
* Klasse [IShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)