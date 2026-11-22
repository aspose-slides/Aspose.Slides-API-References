---
title: series_groups property
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## series_groups ιδιότητα
Επιστρέφει τις ομάδες των σειρών.
Μόνο για ανάγνωση [`IChartSeriesGroupCollection`](/slides/python-net/el/aspose.slides.charts/ichartseriesgroupcollection).

### Παρατηρήσεις

1) Κάθε ομάδα σειρών περιέχει σειρές με συνδυάσιμους τύπους. Ομάδες 
            combinable series types defined and described with CombinableSeriesTypesGroup 
            enum.
            Επίσης κάθε ομάδα σειρών περιέχει σειρές που σχεδιάζονται είτε 
            σε κύριους άξονες είτε σε δευτερεύοντες άξονες (όχι και στις δύο περιπτώσεις στην ίδια ομάδα).
            Έτσι, η αρχή της ομαδοποίησης σειρών είναι η ομαδοποίηση κατά ομάδες τύπων που αναφέρθηκαν 
            παραπάνω και κατά τύπο σχεδίασης κύριου/δευτερεύοντος.
            
            2) Η ομάδα σειρών περιέχει ορισμένες ιδιότητες σειρών που είναι κοινές για 
            κάθε σειρά στην ομάδα ("series group properties").
            Το "Series group properties" στην κλάση ChartSeriesGroup είναι ανάγνωση/εγγραφή.
            Κάθε ένα από τα "series group properties" μπορεί να έχει μια μόνο για ανάγνωση προβολή στην κλάση ChartSeries.

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