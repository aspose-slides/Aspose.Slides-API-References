---
title: get_SeriesGroup()
second_title: Aspose.Slides για C++ API Αναφορά
description: 
type: docs
weight: 222
url: /el/aspose.slides.charts/chartdata/get_seriesgroup/
---
## ChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) μέθοδος




```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries) override
```

## ChartData::get_SeriesGroup(int32_t) μέθοδος


Επιστρέφει την ομάδα σειρών στον καθορισμένο δείκτη.

```cpp
System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::ChartData::get_SeriesGroup(int32_t index) override
```

## Παρατηρήσεις


1) Κάθε ομάδα σειρών περιέχει σειρές με συνδυάσιμους τύπους. Οι ομάδες συνδυάσιμων τύπων σειρών ορίζονται και περιγράφονται με το enum CombinableSeriesTypesGroup. Επίσης, κάθε ομάδα σειρών περιέχει σειρές που σχεδιάζονται είτε σε κύριους άξονες είτε σε δευτερεύοντες άξονες (όχι και στις δύο περιπτώσεις σε μία ομάδα). Συνεπώς, η αρχή της ομαδοποίησης σειρών είναι η ομαδοποίηση κατά τις παραπάνω ομάδες τύπων και κατά τον τύπο σχεδίασης κύριου/δευτερεύοντος άξονα. 2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα (\"ιδιότητες ομάδας σειρών\"). \"ιδιότητες ομάδας σειρών\" στην κλάση [ChartSeriesGroup](../../chartseriesgroup/) είναι ανάγνωση/εγγραφή. Κάθε μία από τις \"ιδιότητες ομάδας σειρών\" μπορεί να έχει μια προβολή μόνο για ανάγνωση στην κλάση [ChartSeries](../../chartseries/). 
## Δείτε επίσης

* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChartSeriesGroup](../../ichartseriesgroup/)
* Κλάση [IChartSeries](../../ichartseries/)
* Κλάση [ChartData](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)