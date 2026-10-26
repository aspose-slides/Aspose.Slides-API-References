---
title: get_SeriesGroup()
second_title: Aspose.Slides για C++ API Αναφορά
description: 
type: docs
weight: 222
url: /el/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) μέθοδος




```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) μέθοδος


Επιστρέφει την ομάδα των σειρών στον καθορισμένο δείκτη.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## Παρατηρήσεις


1) Κάθε ομάδα σειρών περιλαμβάνει σειρές με συνδυάσιμους τύπους. Οι ομάδες συνδυαζόμενων τύπων σειρών ορίζονται και περιγράφονται με το CombinableSeriesTypesGroup enum. Επίσης, κάθε ομάδα σειρών περιέχει σειρές που σχεδιάζονται είτε σε κύριους άξονες είτε σε δευτερεύοντες άξονες (όχι και στις δύο περιπτώσεις στην ίδια ομάδα). Έτσι, η αρχή ομαδοποίησης σειρών είναι η ομαδοποίηση κατά τις παραπάνω ομάδες τύπων και κατά τον τύπο σχεδίασης κύριου/δευτερεύοντος άξονα. 2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειρών»). Οι «ιδιότητες ομάδας σειρών» στην [ChartSeriesGroup](../../chartseriesgroup/) κλάση είναι read/write. Κάθε μία από τις «ιδιότητες ομάδας σειρών» μπορεί να έχει μια read-only προβολή στην [ChartSeries](../../chartseries/) κλάση. 
## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeriesGroup](../../ichartseriesgroup/)
* Class [IChartSeries](../../ichartseries/)
* Class [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)