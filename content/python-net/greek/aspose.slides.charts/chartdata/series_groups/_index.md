---
title: series_groups property
second_title: Aspose.Slides για Python μέσω .NET API αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups ιδιότητα
Λαμβάνει τις ομάδες των σειρών.
            Μόνο για ανάγνωση [`IChartSeriesGroupCollection`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroupcollection).


### Παρατηρήσεις

1) Κάθε ομάδα σειρών περιέχει σειρές με συμβατούς τύπους. Οι ομάδες των 
            συμβατών τύπων σειρών ορίζονται και περιγράφονται με τον enum 
            CombinableSeriesTypesGroup. 
            Επίσης κάθε ομάδα σειρών περιέχει σειρές που σχεδιάζονται είτε 
            σε πρώτους άξονες είτε σε δευτερεύοντες άξονες (όχι και τα δύο στην ίδια ομάδα). 
            Έτσι, η αρχή ομαδοποίησης σειρών είναι η ομαδοποίηση κατά τις 
            ομάδες τύπων που αναφέρθηκαν παραπάνω και κατά τύπο σχεδίασης 
            πρώτου/δευτερεύοντος.
            
            2) Η ομάδα σειρών περιέχει κάποιες ιδιότητες σειρών που είναι κοινές για 
            κάθε σειρά στην ομάδα ("ιδιότητες ομάδας σειρών").
            "Ιδιότητες ομάδας σειρών" στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή.
            Κάθε μία από τις "ιδιότητες ομάδας σειρών" μπορεί να έχει μια μόνο για 
            ανάγνωση προβολή στην κλάση ChartSeries.

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