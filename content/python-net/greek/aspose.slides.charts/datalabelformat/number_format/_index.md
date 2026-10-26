---
title: number_format property
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/datalabelformat/number_format/
weight: 80
---
## number_format ιδιότητα
Represents the format string for the DataLabels object.
            Ανάγνωση/εγγραφή **str**.

### Παρατηρήσεις

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this
            ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας NumberFormat για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection.
            Όταν αυτή η ιδιότητα ορίζεται με μια τιμή, η τιμή αυτή ορίζεται επίσης για την ιδιότητα NumberFormat για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection
            (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" causes all DataLabels[i].NumberFormat to equal to val).

### Ορισμός:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```

### Δείτε επίσης
* κλάση [`DataLabelFormat`](/slides/python-net/el/aspose.slides.charts/datalabelformat)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)