---
title: AddDataPointForMapSeries
second_title: Référence de l'API Aspose.Slides pour .NET
description: Crée le nouveau point de données et lajoute à la fin de la collection. Applicable pour les séries dont le type de graphique est Map.
type: docs
weight: 150
url: /fr/net/aspose.slides.charts/ichartdatapointcollection/adddatapointformapseries/
---
## IChartDataPointCollection.AddDataPointForMapSeries method

Crée le nouveau point de données et l'ajoute à la fin de la collection. Applicable pour les séries dont le type de graphique est Map.

```csharp
public IChartDataPoint AddDataPointForMapSeries(IChartDataCell value)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| value | IChartDataCell | Valeur de couleur du point de données |

### Return_Value

Nouveau point de données.

### Exemples

```csharp
[C#]
using (Presentation pres = new Presentation())
{
   IChart chart = sourcePres.Slides[0].Shapes.AddChart(ChartType.Map, 50, 50, 500, 400, false);
   IChartDataWorkbook wb = chart.ChartData.ChartDataWorkbook;

   IChartSeries series = chart.ChartData.Series.Add(ChartType.Map);
   series.DataPoints.AddDataPointForMapSeries(wb.GetCell(0, "B2", 5));
   series.DataPoints.AddDataPointForMapSeries(wb.GetCell(0, "B3", 1));
   series.DataPoints.AddDataPointForMapSeries(wb.GetCell(0, "B4", 10));
}
```

### Voir également

* interface [IChartDataPoint](../../ichartdatapoint)
* interface [IChartDataCell](../../ichartdatacell)
* interface [IChartDataPointCollection](../../ichartdatapointcollection)
* espace de noms [Aspose.Slides.Charts](../../ichartdatapointcollection)
* Assemblée [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->