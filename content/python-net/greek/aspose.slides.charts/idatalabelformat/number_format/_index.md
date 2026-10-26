---
title: number_format property
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description:
type: docs
url: /el/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format ιδιότητα
Αναπαριστά τη συμβολοσειρά μορφής για το αντικείμενο DataLabels.
Ανάγνωση/Εγγραφή **str**.

### Παρατηρήσεις

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας NumberFormat για τις νέες ετικέτες δεδομένων στη συλλογή DataLabelCollection.
Όταν αυτή η ιδιότητα ορίζεται με μια τιμή, η τιμή αυτή ορίζεται επίσης για την ιδιότητα NumberFormat για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection
(π.χ. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" προκαλεί όλα τα DataLabels[i].NumberFormat να είναι ίσα με val).

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
* κλάση [`IDataLabelFormat`](/slides/python-net/el/aspose.slides.charts/idatalabelformat)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)