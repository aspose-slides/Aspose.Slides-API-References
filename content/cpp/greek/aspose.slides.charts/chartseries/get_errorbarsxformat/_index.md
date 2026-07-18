---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αντιπροσωπεύει τα ErrorBars της σειράς με κατεύθυνση X.
type: docs
weight: 222
url: /el/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() μέθοδος


Αντιπροσωπεύει τα ErrorBars της σειράς με κατεύθυνση X.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## Παρατηρήσεις


Τα ErrorBars με κατεύθυνση X είναι διαθέσιμα για σειρές τύπου area, bar, scatter και bubble. Για οποιονδήποτε άλλο τύπο διαγράμματος η ιδιότητα αυτή επιστρέφει null (συμπεριλαμβανομένων των 3D διαγραμμάτων). Σε περίπτωση προσαρμοσμένων τιμών χρησιμοποιήστε τη συλλογή DataPoints για να καθορίσετε την τιμή (με την ιδιότητα [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Μόνο για ανάγνωση [IErrorBarsFormat](../../ierrorbarsformat/). 
## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IErrorBarsFormat](../../ierrorbarsformat/)
* Κλάση [ChartSeries](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)