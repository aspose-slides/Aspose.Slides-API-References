---
title: get_ErrorBarsYFormat()
second_title: Αναφορά API Aspose.Slides για C++
description: Αναπαριστά τα ErrorBars της σειράς με κατεύθυνση Y.
type: docs
weight: 235
url: /el/aspose.slides.charts/ichartseries/get_errorbarsyformat/
---
## IChartSeries::get_ErrorBarsYFormat() μέθοδος


Αναπαριστά τα ErrorBars της σειράς με κατεύθυνση Y.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsYFormat()=0
```

## Παρατηρήσεις


Τα ErrorBars με κατεύθυνση Y είναι διαθέσιμα για σειρές τύπου area, bar, line, scatter και bubble. Για οποιουσδήποτε άλλους τύπους διαγράμματος αυτή η ιδιότητα επιστρέφει null (συμπεριλαμβανομένων των 3D διαγραμμάτων). Σε περίπτωση προσαρμοσμένων τιμών χρησιμοποιήστε τη συλλογή DataPoints για να καθορίσετε την τιμή (με ιδιότητα [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)). 

Μόνο για ανάγνωση [IErrorBarsFormat](../../ierrorbarsformat/). 
## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IErrorBarsFormat](../../ierrorbarsformat/)
* Κλάση [IChartSeries](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)