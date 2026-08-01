---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Als de categorie bestaat in de verzameling, retourneer deze. Anders maakt het een nieuwe grafiektategorie aan van IChartDataCell en voegt deze toe aan de verzameling.
type: docs
weight: 53
url: /nl/aspose.slides.charts/ichartcategorycollection/add/
---
## IChartCategoryCollection::Add(System::SharedPtr\<IChartDataCell\>) methode


Als de categorie bestaat in de verzameling, retourneer deze. Anders maakt het een nieuwe grafiektategorie aan van [IChartDataCell](../../ichartdatacell/) en voegt deze toe aan de verzameling.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<IChartDataCell> chartDataCell)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chartDataCell | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) gebruikt om een grafiektategorie te maken. |

### Retourwaarde

Toegevoegde of bestaande categorie.



## IChartCategoryCollection::Add(System::SharedPtr\<System::Object\>) methode


Maakt een nieuwe [IChartCategory](../../ichartcategory/) van de waarde en voegt deze toe aan de collectie.

```cpp
virtual System::SharedPtr<IChartCategory> Aspose::Slides::Charts::IChartCategoryCollection::Add(System::SharedPtr<System::Object> value)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | De waarde. |

### Retourwaarde

Toegevoegd [IChartCategory](../../ichartcategory/).

## Opmerkingen



Deze methode voegt een werkblad toe met de naam AUTO_DATA en voegt daar alle waarden toe. Als u [IChartDataWorkbook](../../ichartdataworkbook/) gebruikt om celwaarden toe te voegen of te bewerken, zorg er dan voor dat u dit werkblad niet gebruikt. Het maximale aantal waarden dat met deze methode wordt toegevoegd mag niet hoger zijn dan 16711680



## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChartCategory](../../ichartcategory/)
* Klasse [IChartDataCell](../../ichartdatacell/)
* Klasse [IChartCategoryCollection](../)
* Klasse [Object](../../../system/object/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)