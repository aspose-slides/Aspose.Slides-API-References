---
title: series_groups property
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups ιδιότητα
Αποκτά τις ομάδες σειρών.
Μόνο για ανάγνωση [`IChartSeriesGroupCollection`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroupcollection).

### Παρατηρήσεις

1) Κάθε ομάδα σειρών περιέχει σειρές με συνδυάσιμους τύπους. Οι ομάδες των συνδυάσιμων τύπων σειρών ορίζονται και περιγράφονται με το enum CombinableSeriesTypesGroup.
   Επίσης, κάθε ομάδα σειρών περιέχει σειρές που σχεδιάζονται είτε σε πρωτεύοντες άξονες είτε σε δευτερεύοντες άξονες (όχι και στις δύο περιπτώσεις στην ίδια ομάδα).
   Έτσι, η αρχή της ομαδοποίησης σειρών είναι η ομαδοποίηση κατά τις παραπάνω ομάδες τύπων και κατά τον τύπο σχεδίασης πρωτεύοντος/δευτερεύοντος.

2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειρών που είναι κοινές για κάθε σειρά στην ομάδα («ιδιότητες ομάδας σειρών»).
   Οι «ιδιότητες ομάδας σειρών» στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή.
   Κάθε μία από τις «ιδιότητες ομάδας σειρών» μπορεί να έχει μια προβολή μόνο για ανάγνωση στην κλάση ChartSeries.

### Ορισμός:
```python
@property
def series_groups(self):
    ...
```

### Δείτε επίσης
* κλάση [`IChartData`](/slides/python-net/el/aspose.slides.charts/ichartdata)
* κλάση [`IChartSeriesGroupCollection`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroupcollection)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)