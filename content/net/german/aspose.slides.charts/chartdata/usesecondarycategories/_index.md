---  
title: UseSecondaryCategories
second_title: Aspose.Sildes für .NET API Referenz  
description: Wenn falsch, gibt die Eigenschaft SecondaryCategoriesaspose.slides.charts/chartdata/secondarycategories null zurück und die Daten in der Eigenschaft Categoriesaspose.slides.charts/chartdata/categories werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn wahr, werden die Daten in der Eigenschaft SecondaryCategoriesaspose.slides.charts/chartdata/secondarycategories für sekundäre Serien verwendet und die Daten in der Eigenschaft Categoriesaspose.slides.charts/chartdata/categories werden für primäre Serien verwendet. Lese-/schreibbare Boolean.
type: docs
weight: 80  
url: /de/aspose.slides.charts/chartdata/usesecondarycategories/
---  

## ChartData.UseSecondaryCategories Eigenschaft  

Wenn falsch, gibt die [`SecondaryCategories`](../secondarycategories) Eigenschaft null zurück und die Daten in der [`Categories`](../categories) Eigenschaft werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn wahr, werden die Daten in der [`SecondaryCategories`](../secondarycategories) Eigenschaft für sekundäre Serien verwendet und die Daten in der [`Categories`](../categories) Eigenschaft werden für primäre Serien verwendet. Lese-/schreibbare Boolean.  

```csharp  
public bool UseSecondaryCategories { get; set; }  
```  

### Beispiele  

Beispiel. Welche Kategorien sind mit Serien verbunden - ChartData.Categories oder ChartData.SecondaryCategories?  

```csharp  
if (series.PlotOnSecondAxis && series.Chart.ChartData.UseSecondaryCategories)  
{  
    // verwandte Kategorien sind series.Chart.ChartData.SecondaryCategories  
}  
else  
{  
    // verwandte Kategorien sind series.Chart.ChartData.Categories  
}  
```  

### Siehe Auch  

* Klasse [ChartData](../../chartdata)  
* Namespace [Aspose.Slides.Charts](../../chartdata)  
* Assembly [Aspose.Slides](../../../)  

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->  