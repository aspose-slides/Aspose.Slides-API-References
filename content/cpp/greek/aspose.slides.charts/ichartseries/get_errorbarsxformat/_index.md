---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Αντιπροσωπεύει τα ErrorBars της σειράς με κατεύθυνση X.
type: docs
weight: 222
url: /el/aspose.slides.charts/ichartseries/get_errorbarsxformat/
---
## IChartSeries::get_ErrorBarsXFormat() μέθοδος

Αντιπροσωπεύει τα ErrorBars της σειράς με κατεύθυνση X.

```cpp
virtual System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::IChartSeries::get_ErrorBarsXFormat()=0
```

## Παρατηρήσεις

Τα ErrorBars με κατεύθυνση X είναι διαθέσιμα για σειρές τύπου area, bar, scatter και bubble. Για οποιουσδήποτε άλλους τύπους διαγράμματος αυτή η ιδιότητα επιστρέφει null (συμπεριλαμβανομένων των 3D διαγραμμάτων). Σε περίπτωση προσαρμοσμένων τιμών χρησιμοποιήστε τη συλλογή DataPoints για να καθορίσετε την τιμή (με την ιδιότητα [IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/)).

Μόνο για ανάγνωση [IErrorBarsFormat](../../ierrorbarsformat/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IErrorBarsFormat](../../ierrorbarsformat/)
* Κλάση [IChartSeries](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)