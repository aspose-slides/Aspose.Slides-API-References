---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides for C++ Référence de l'API
description: Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont chartType est l'un des sous-types Column ou Bar (voir également ChartTypeCharacterizer.IsChartTypeColumn(ChartType) et ChartTypeCharacterizer.IsChartTypeBar(ChartType) méthode).
type: docs
weight: 196
url: /fr/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) méthode

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des [Column](../../../aspose.slides/column/) ou aux sous-types Bar (voir également [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) et [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) méthode).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Valeur du point de données |

### Valeur de retour

Nouveau point de données.

## IChartDataPointCollection::AddDataPointForBarSeries(double) méthode

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des [Column](../../../aspose.slides/column/) ou aux sous-types Bar (voir également [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) et [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) méthode).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
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
* Classe [IChartDataPointCollection](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)