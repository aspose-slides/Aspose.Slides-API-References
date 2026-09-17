---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος υπολογισμένα από το αποδοθέν περιεχόμενό του.

### Επιστρέφει

Μια **aspose.slides.RectangleF** που αντιπροσωπεύει τα οπτικά όρια του σχήματος
             σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις

Το επιστραφόμενο ορθογώνιο αντιπροσωπεύει τα άξονες-ευθυγραμμισμένα όρια όλου του περιεχομένου
             που παράχθηκε από το σχήμα κατά τη διάρκεια της απόδοσης στο χώρο συντεταγμένων της διαφάνειας.
Αυτά τα όρια μπορεί να διαφέρουν από τα μοντέλα ορίων του σχήματος
             ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
             και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδοθέν περιεχόμενο εκτείνεται
             πέρα από την αρχή της διαφάνειας.
Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετικές με την απόδοση όπως
             μετασχηματισμούς (π.χ., περιστροφή), πλάτος γραμμής και ενώσεις,
             διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt, και άλλα εφέ διάταξης
             που επηρεάζουν την τελική εμφανιζόμενη μορφή του σχήματος.
Τα επιστραφόμενα όρια δεν περικόπτονται στο ορθογώνιο της διαφάνειας.

### Δείτε επίσης
* κλάση [`GraphicalObject`](/slides/python-net/el/aspose.slides/graphicalobject)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)