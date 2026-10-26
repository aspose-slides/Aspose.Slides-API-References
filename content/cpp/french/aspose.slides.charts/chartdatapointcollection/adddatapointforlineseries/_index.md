---
title: AddDataPointForLineSeries()
second_title: Référence API Aspose.Slides pour C++
description: "Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable aux séries dont le chartType est l'un des sous-types Line (voir aussi la méthode ChartTypeCharacterizer::IsChartTypeLine(ChartType))."
type: docs
weight: 222
url: /fr/aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries/
---
## ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) method

Crée le nouveau point de données et l’ajoute à la fin de la collection. Applicable aux séries dont le chartType est l’un des sous-types Line (voir aussi [ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) méthode).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Valeur du point de données. |

### Valeur de retour

Nouveau point de données.

## ChartDataPointCollection::AddDataPointForLineSeries(double) method

Crée le nouveau point de données et l’ajoute à la fin de la collection. Applicable aux séries dont le chartType est l’un des sous-types Line (voir aussi [ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) méthode).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(double value) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| value | **double** | Valeur du point de données. |

### Valeur de retour

Nouveau point de données.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IChartDataPoint](../../ichartdatapoint/)
* Classe [IChartDataCell](../../ichartdatacell/)
* Classe [ChartDataPointCollection](../)
* Espace de noms [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)