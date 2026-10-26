---
title: IChartDataWorksheetCollection
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente la collection de feuilles de calcul du classeur de données du graphique.
type: docs
url: /fr/com.aspose.slides/ichartdataworksheetcollection/
---
**Toutes les interfaces implémentées:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Représente la collection de feuilles de calcul du classeur de données du graphique.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Méthodes

| Méthode | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Renvoie la feuille de calcul par index. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```

Renvoie la feuille de calcul par index.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index | int | Index de la feuille de calcul dans la collection. |

**Renvoie:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Instance de IChartDataWorksheet.