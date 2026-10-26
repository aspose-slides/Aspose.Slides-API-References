---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος υπολογισμένα από το αποτυπωμένο περιεχόμενό του.

### Επιστρέφει

Ένα [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef) που αντιπροσωπεύει τα οπτικά όρια του σχήματος
              σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Σημειώσεις

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα ευθυγράμμιστα όρια όλου του περιεχομένου
              που παράγεται από το σχήμα κατά τη λειτουργία απόδοσης στον χώρο συντεταγμένων της διαφάνειας.

              Αυτά τα όρια μπορεί να διαφέρουν από τα όρια του μοντέλου του σχήματος
              ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
              [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
              και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποτυπωμένο περιεχόμενο επεκτείνεται
              πέρα από την αρχή της διαφάνειας.

              Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετικές με την απόδοση όπως
              μετασχηματισμοί (π.χ., περιστροφή), πλάτος και ενώσεις γραμμή,
              διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt, και άλλες επιδράσεις διάταξης
              που επηρεάζουν την τελική εμφανιζόμενη μορφή του σχήματος.

              Τα επιστρεφόμενα όρια δεν περικοπώνται στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`AutoShape`](/slides/python-net/el/aspose.slides/autoshape)
* κλάση [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)