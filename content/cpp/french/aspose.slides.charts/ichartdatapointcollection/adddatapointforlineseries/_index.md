---
title: AddDataPointForLineSeries()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Line (voir également la méthode ChartTypeCharacterizer.IsChartTypeLine(ChartType)).
type: docs
weight: 157
url: /fr/aspose.slides.charts/ichartdatapointcollection/adddatapointforlineseries/
---
## IChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) méthode

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Line (voir aussi [ChartTypeCharacterizer.IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) méthode).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Valeur du point de données. |

### Valeur de retour

Nouveau point de données.

## IChartDataPointCollection::AddDataPointForLineSeries(double) méthode

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Line (voir aussi [ChartTypeCharacterizer.IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) méthode).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForLineSeries(double value)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **double** | Valeur du point de données. |

### Valeur de retour

Nouveau point de données.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataPoint](../../ichartdatapoint/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [IChartDataPointCollection](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Bibliothèque [Aspose.Slides](../../../)