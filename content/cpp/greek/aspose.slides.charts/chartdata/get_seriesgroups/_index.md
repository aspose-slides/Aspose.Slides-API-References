---
title: get_SeriesGroups()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει τις ομάδες των σειρών. Μόνο για ανάγνωση IChartSeriesGroupCollection.
type: docs
weight: 27
url: /el/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() μέθοδος

Λαμβάνει τις ομάδες των σειρών. Μόνο για ανάγνωση [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## Παρατηρήσεις

1) Κάθε ομάδα σειρών περιέχει σειρές με συνδυάσιμους τύπους. Οι ομάδες συνδυάσιμων τύπων σειρών καθορίζονται και περιγράφονται με το enum CombinableSeriesTypesGroup. Επίσης, κάθε ομάδα σειρών περιέχει σειρές που σχεδιάζονται είτε σε πρωτεύοντες άξονες είτε σε δευτερεύοντες άξονες (όχι και στις δύο περιπτώσεις στην ίδια ομάδα). Έτσι, η αρχή της ομαδοποίησης σειρών είναι η ομαδοποίηση ανά τύπους ομάδων που αναφέρθηκαν παραπάνω και ανά τύπο σχεδίασης πρωτεύοντος/δευτερεύοντος.

2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα ("series group properties"). "Series group properties" στην κλάση [ChartSeriesGroup](../../chartseriesgroup/) είναι ανάγνωση/εγγραφή. Κάθε μία από τις "series group properties" μπορεί να έχει μια προβολή μόνο-ανάγνωση στην κλάση [ChartSeries](../../chartseries/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Κλάση [ChartData](../)
* Χώρος ονόματος [Aspose::Slides::Charts](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)