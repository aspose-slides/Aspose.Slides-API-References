---
title: get_SeriesGroups()
second_title: Αναφορά API Aspose.Slides για C++
description: Λαμβάνει τις ομάδες σειρών. Μόνο ανάγνωση IChartSeriesGroupCollection.
type: docs
weight: 27
url: /el/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() μέθοδος

Παίρνει τις ομάδες των σειρών. Μόνο ανάγνωση [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## Παρατηρήσεις

1) Κάθε ομάδα σειρών περιέχει σειρές με συμβιβαστικούς τύπους. Οι ομάδες συμβιβαστικών τύπων σειρών ορίζονται και περιγράφονται με το enum CombinableSeriesTypesGroup. Επίσης, κάθε ομάδα σειρών περιέχει σειρές που σχεδιάζονται είτε σε κύριους άξονες είτε σε δευτερεύοντες άξονες (όχι και στις δύο περιπτώσεις στην ίδια ομάδα). Έτσι, η αρχή ομαδοποίησης σειρών είναι η ομαδοποίηση κατά τις παραπάνω ομάδες τύπων και κατά τύπο σχεδίασης κύριου/δευτερεύοντος άξονα.

2) Η ομάδα σειρών περιέχει κάποιες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειρών»). Οι «ιδιότητες ομάδας σειρών» στην [ChartSeriesGroup](../../chartseriesgroup/) κλάση είναι ανάγνωση/εγγραφή. Κάθε μία από τις «ιδιότητες ομάδας σειρών» μπορεί να έχει μια μόνο-ανάγνωση προβολή στην [ChartSeries](../../chartseries/) κλάση.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* Κλάση [IChartData](../)
* Χώρος ονομάτων [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)