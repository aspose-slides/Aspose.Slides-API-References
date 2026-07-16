---
title: AddDataPointForPieSeries()
second_title: Référence API Aspose.Slides pour C++
description: "Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Pie (voir également la méthode ChartTypeCharacterizer::IsChartTypePie(ChartType))."
type: docs
weight: 287
url: /fr/aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries/
---
## ChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr\<IChartDataCell\>) méthode


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Pie (voir également [ChartTypeCharacterizer::IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) méthode).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr<IChartDataCell> value) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Data point Value |

### Valeur de retour

New data point.

## ChartDataPointCollection::AddDataPointForPieSeries(double) méthode


Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Pie (voir également [ChartTypeCharacterizer::IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) méthode).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForPieSeries(double value) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **double** | Data point Value |

### Valeur de retour

New data point.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataPoint](../../ichartdatapoint/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [ChartDataPointCollection](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)