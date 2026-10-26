---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een nieuwe cel toe aan de collectie.
type: docs
weight: 53
url: /nl/aspose.slides.charts/ichartcellcollection/add/
---
## IChartCellCollection::Add(System::SharedPtr\<IChartDataCell\>) methode


Voeg een nieuwe cel toe aan de collectie.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Nieuwe cel om toe te voegen. |

## IChartCellCollection::Add(System::SharedPtr\<System::Object\>) methode


Maakt [IChartDataCell](../../ichartdatacell/) aan van de opgegeven waarde en voegt deze toe aan de collectie.

```cpp
virtual void Aspose::Slides::Charts::IChartCellCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | De waarde. |
## Opmerkingen



Deze methode voegt een werkblad met de naam AUTO_DATA toe en voegt daar alle waarden toe. Als u [IChartDataWorkbook](../../ichartdataworkbook/) gebruikt om [Cell](../../../aspose.slides/cell/) waarden toe te voegen of te bewerken, zorg er dan voor dat u dit werkblad niet gebruikt. Het maximale aantal waarden dat met deze methode wordt toegevoegd mag niet hoger zijn dan 16711680



## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [IChartCellCollection](../)
* Klasse [Object](../../../system/object/)
* Naamruimte [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)