---
title: show_label_value_from_cell property
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell ιδιότητα
Αντιπροσωπεύει τη συμπεριφορά εμφάνισης της τιμής του κελιού ετικέτας δεδομένων ενός καθορισμένου διαγράμματος.
            Η τιμή True εμφανίζει την τιμή του κελιού. Η τιμή False την αποκρύπτει.
            Ανάγνωση/εγγραφή **bool**.

### Παρατηρήσεις

Αν ο γονέας αυτού του αντικειμένου DataLabelFormat είναι μια συλλογή DataLabelCollection ετικετών δεδομένων, τότε αυτή η
            ιδιότητα παίρνει ή ορίζει την προεπιλεγμένη τιμή της ιδιότητας ShowLabelValueFromCell για τις νέες ετικέτες
            δεδομένων στη συλλογή DataLabelCollection.
            Ορίζοντας αυτήν την ιδιότητα με τιμή, ορίζεται επίσης αυτή η τιμή στην ιδιότητα ShowLabelValueFromCell
            για όλες τις ετικέτες δεδομένων στη συλλογή DataLabelCollection
            (π.χ. "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" προκαλεί
            όλα τα DataLabels[i].ShowLabelValueFromCell να είναι ίσα με val).

### Ορισμός:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```

### Δείτε επίσης
* κλάση [`DataLabelFormat`](/slides/python-net/el/aspose.slides.charts/datalabelformat)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)