---
title: series_groups property
second_title: Aspose.Slides για Python μέσω .NET αναφορά API
description: 
type: docs
url: /el/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups ιδιότητα
Αποκτά τις ομάδες σειρών.
Μόνο ανάγνωση [`IChartSeriesGroupCollection`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroupcollection).


### Παρατηρήσεις

1) Κάθε ομάδα σειρών περιέχει σειρές με συνδυάσιμους τύπους. Οι ομάδες 
            συνδυάσιμων τύπων σειρών ορίζονται και περιγράφονται με το enum 
            CombinableSeriesTypesGroup. 
            Επίσης, κάθε ομάδα σειρών περιέχει σειρές που σχεδιάζονται είτε 
            σε κύριους άξονες είτε σε δευτερεύοντες άξονες (όχι και στις δύο περιπτώσεις στην ίδια ομάδα). 
            Συνεπώς, η αρχή της ομαδοποίησης σειρών είναι η ομαδοποίηση κατά τις παραπάνω ομάδες τύπων 
            και κατά τύπο σχεδίασης κύριου/δευτερεύοντος άξονα.
            
2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειράς που είναι κοινές για 
            κάθε σειρά στην ομάδα ("ιδιότητες ομάδας σειρών").
            "Series group properties" in ChartSeriesGroup class is ανάγνωση/εγγραφή.
            Κάθε μια από τις "ιδιότητες ομάδας σειρών" μπορεί να έχει μια μόνο ανάγνωση προβολή στην ChartSeries class.

### Ορισμός:
```python
@property
def series_groups(self):
    ...
```


### Δείτε επίσης
* κλάση [`ChartData`](/slides/python-net/el/aspose.slides.charts/chartdata)
* κλάση [`IChartSeriesGroupCollection`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroupcollection)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)