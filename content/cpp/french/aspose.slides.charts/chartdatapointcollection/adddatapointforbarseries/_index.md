---
title: AddDataPointForBarSeries()
second_title: Référence API Aspose.Slides pour C++
description: "Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Column ou Bar (voir également les méthodes ChartTypeCharacterizer::IsChartTypeColumn(ChartType) et ChartTypeCharacterizer::IsChartTypeBar(ChartType))."
type: docs
weight: 261
url: /fr/aspose.slides.charts/chartdatapointcollection/adddatapointforbarseries/
---
## ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) méthode


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des [Column](../../../aspose.slides/column/) ou aux sous-types Bar (voir également les méthodes [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) et [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/)).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Valeur du point de données |

### Valeur de retour

Nouveau point de données.

## ChartDataPointCollection::AddDataPointForBarSeries(double) méthode


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des [Column](../../../aspose.slides/column/) ou aux sous-types Bar (voir également les méthodes [ChartTypeCharacterizer::IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) et [ChartTypeCharacterizer::IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/)).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForBarSeries(double value) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **double** | Valeur du point de données |

### Valeur de retour

Nouveau point de données.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataPoint](../../ichartdatapoint/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [ChartDataPointCollection](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)