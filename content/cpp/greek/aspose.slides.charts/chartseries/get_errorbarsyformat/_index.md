---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αναπαριστά τα ErrorBars της σειράς με κατεύθυνση Y.
type: docs
weight: 235
url: /el/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() μέθοδος

Αναπαριστά τα ErrorBars της σειράς με κατεύθυνση Y.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## Σχόλια

Τα ErrorBars με διεύθυνση Y είναι διαθέσιμα για σειρές τύπου area, bar, line, scatter και bubble. Για οποιονδήποτε άλλο τύπο διαγράμματος αυτή η ιδιότητα επιστρέφει null (συμπεριλαμβανομένων των 3D διαγραμμάτων). Σε περίπτωση προσαρμοσμένων τιμών, χρησιμοποιήστε τη συλλογή DataPoints για να καθορίσετε την τιμή (με [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) ιδιότητα).

Μόνο ανάγνωση [IErrorBarsFormat](../../ierrorbarsformat/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IErrorBarsFormat](../../ierrorbarsformat/)
* Κλάση [ChartSeries](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)