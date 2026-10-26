---
title: AddTable()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuwe tabel en voegt deze toe aan het einde van de vormverzameling.
type: docs
weight: 430
url: /nl/aspose.slides/ishapecollection/addtable/
---
## IShapeCollection::AddTable(float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) methode

Maakt een nieuwe tabel en voegt deze toe aan het einde van de vormverzameling.

```cpp
virtual System::SharedPtr<ITable> Aspose::Slides::IShapeCollection::AddTable(float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | **float** | De x-coördinaat van de tabel, in punten. |
| y | **float** | De y-coördinaat van de tabel, in punten. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Een array van doubles die de breedtes van de kolommen van de tabel weergeeft, in punten. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Een array van doubles die de hoogtes van de rijen van de tabel weergeeft, in punten. |

### Retourwaarde

De nieuw aangemaakte [ITable](../../itable/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ITable](../../itable/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)