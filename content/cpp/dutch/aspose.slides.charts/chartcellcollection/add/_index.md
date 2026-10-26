---
title: Add()
second_title: Aspose.Slides voor C++ API Referentie
description: Voeg een nieuwe cel toe aan de verzameling.
type: docs
weight: 53
url: /nl/aspose.slides.charts/chartcellcollection/add/
---
## ChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) methode

Voeg een nieuwe cel toe aan de verzameling.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<IChartDataCell> cell) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Nieuwe cel om toe te voegen. |

## ChartCellCollection::Add(System::SharedPtr\<System::Object\>) methode

Maakt [ChartDataCell](../../chartdatacell/) aan vanuit de opgegeven waarde en voegt deze toe aan de verzameling.

```cpp
void Aspose::Slides::Charts::ChartCellCollection::Add(System::SharedPtr<System::Object> value) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | De waarde. |

## Opmerkingen

Deze methode voegt een werkblad met de naam AUTO_DATA toe en voegt daar alle waarden toe. Als je [ChartDataWorkbook](../../chartdataworkbook/) gebruikt om [Cell](../../../aspose.slides/cell/) waarden toe te voegen of te bewerken, zorg er dan voor dat je dit werkblad niet gebruikt. Het maximale aantal waarden dat met deze methode wordt toegevoegd mag 16711680 niet overschrijden.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [ChartCellCollection](../)
* Klasse [Object](../../../system/object/)
* Naamruimte [Aspose::Slides::Charts](../../)
* Bibliotheek [Aspose.Slides](../../../)