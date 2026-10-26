---
title: InsertTable()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuwe tabel aan en voegt deze in de shape-collectie in op de opgegeven index.
type: docs
weight: 482
url: /nl/aspose.slides/shapecollection/inserttable/
---
## ShapeCollection::InsertTable(int32_t, float, float, System::ArrayPtr\<double\>, System::ArrayPtr\<double\>) methode

Maakt een nieuwe tabel aan en voegt deze in de shape-collectie in op de opgegeven index.

```cpp
System::SharedPtr<ITable> Aspose::Slides::ShapeCollection::InsertTable(int32_t index, float x, float y, System::ArrayPtr<double> columnWidths, System::ArrayPtr<double> rowHeights) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop de tabel moet worden ingevoegd. |
| x | **float** | De x-coördinaat van de tabel, in punten. |
| y | **float** | De y-coördinaat van de tabel, in punten. |
| columnWidths | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Een array van doubles die de breedtes van de kolommen van de tabel vertegenwoordigt, in punten. |
| rowHeights | [System::ArrayPtr](../../../system/arrayptr/)\<**double**\> | Een array van doubles die de hoogtes van de rijen van de tabel vertegenwoordigt, in punten. |

### Retourwaarde

De nieuw aangemaakte [ITable](../../itable/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ITable](../../itable/)
* Klasse [ShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)