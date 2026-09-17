---
title: show_series_name property
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name property
Επιστρέφει ή ορίζει ένα Boolean για να υποδείξει τη συμπεριφορά εμφάνισης του ονόματος σειράς στα ετικέτες δεδομένων σε ένα γράφημα.
            True για εμφάνιση του ονόματος σειράς. False για απόκρυψη.
            Ανάγνωση/εγγραφή **bool**.

### Παρατηρήσεις

Εάν ο γονέας αυτού του DataLabelFormat αντικειμένου είναι μια DataLabelCollection συλλογή ετικετών δεδομένων, τότε αυτή
            η ιδιότητα λαμβάνει ή ορίζει την προεπιλεγμένη τιμή της ShowSeriesName ιδιότητας για τις νέες ετικέτες δεδομένων στη DataLabelCollection συλλογή.
            Ο ορισμός αυτής της ιδιότητας με τιμή επίσης ορίζει αυτήν την τιμή στην ShowSeriesName ιδιότητα
            για όλες τις ετικέτες δεδομένων στη DataLabelCollection συλλογή
            (π.χ. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" οδηγεί στο
            όλα τα DataLabels[i].ShowSeriesName είναι ίσα με val).

### Ορισμός:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```

### Δείτε επίσης
* κλάση [`IDataLabelFormat`](/slides/python-net/el/aspose.slides.charts/idatalabelformat)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)