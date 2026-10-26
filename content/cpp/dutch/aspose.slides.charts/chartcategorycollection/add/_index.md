---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Als de categorie bestaat in de collectie, wordt deze geretourneerd. Anders wordt een nieuwe grafiekcategorie gemaakt van IChartDataCell en toegevoegd aan de collectie.
type: docs
weight: 92
url: /nl/aspose.slides.charts/chartcategorycollection/add/
---
## ChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) methode

Als de categorie al bestaat in de collectie, wordt deze geretourneerd. Anders wordt een nieuwe grafiekcategorie gemaakt van [IChartDataCell](../../ichartdatacell/) en toegevoegd aan de collectie.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) gebruikt om een grafiekcategorie te maken. |

### Retourwaarde

Toegevoegde of bestaande categorie.

## ChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) methode

Maakt een nieuwe [ChartCategory](../../chartcategory/) van de waarde en voegt deze toe aan de collectie.

```cpp
System::SharedPtr<IChartCategory> Aspose::Slides::Charts::ChartCategoryCollection::Add(System::SharedPtr<System::Object> value) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | De waarde. |

### Retourwaarde

Toegevoegde [IChartCategory](../../ichartcategory/).

## Opmerkingen

Deze methode voegt een werkblad met de naam AUTO_DATA toe en voegt daar alle waarden toe. Als u [ChartDataWorkbook](../../chartdataworkbook/) gebruikt om celwaarden toe te voegen of te bewerken, zorg er dan voor dat u dit werkblad niet gebruikt. Het maximum aantal waarden dat met deze methode toegevoegd mag worden, mag 16711680 niet overschrijden.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartCategory](../../ichartcategory/)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [ChartCategoryCollection](../)
* Klasse [Object](../../../system/object/)
* Naamruimte [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)