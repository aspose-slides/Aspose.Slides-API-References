---
title: RefreshData
second_title: Aspose.Sildes dla .NET – dokumentacja API
description: Odświeża dane wykresu, ponownie ładując je ze źródłowego skoroszytu.
type: docs
weight: 120
url: /pl/aspose.slides.charts/chartdata/refreshdata/
---
## ChartData.RefreshData metoda

Odświeża dane wykresu, ponownie ładując je z źródłowego skoroszytu.

```csharp
public void RefreshData()
```

### Wyjątki

| wyjątek | warunek |
| --- | --- |
| InvalidOperationException | Rzucany, gdy format skoroszytu nie jest obsługiwany lub gdy [`DataSourceType`](../datasourcetype) jest ExternalWorkbook i nie można uzyskać dostępu do zewnętrznego skoroszytu lub go załadować. |

### Uwagi

Jeśli wykres używa zewnętrznego skoroszytu, skoroszyt musi być dostępny w momencie wywołania.

### Przykłady

```csharp
using (var presentation = new Presentation("presentationWithChart.pptx"))
{
    var chart = (IChart)presentation.Slides[0].Shapes[0];
    chart.ChartData.RefreshData();
}
```

### Zobacz także

* klasa [ChartData](../../chartdata)
* przestrzeń nazw [Aspose.Slides.Charts](../../chartdata)
* zbiór [Aspose.Slides](../../../)

<!-- NIEWEDZIANO: wygenerowano przez xmldocmd dla Aspose.Slides.dll -->