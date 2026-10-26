---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API αναφορά
description: 
type: docs
url: /el/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος, υπολογισμένα από το αποδοθέν περιεχόμενό του.

### Επιστρέφει

Ένα [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef) που αντιπροσωπεύει τα οπτικά όρια του σχήματος σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Σχόλια

Το επιστρεφόμενο παραλληλόγραμμο αντιπροσωπεύει τα ευθυγραμμισμένα προς άξονες όρια όλου του περιεχομένου
             που παράγεται από το σχήμα κατά τη διάρκεια της απόδοσης σε χώρο συντεταγμένων διαφάνειας.
            
             Αυτά τα όρια μπορεί να διαφέρουν από τα όρια του μοντέλου του σχήματος
             ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
             και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδοθέν περιεχόμενο επεκτείνεται πέρα από το αρχικό σημείο της διαφάνειας.
            
             Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετικές με την απόδοση, όπως
             μετασχηματισμούς (π.χ., περιστροφή), πλάτος περιγράμματος και ενώσεις,
             διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt, και άλλα εφέ διάταξης που επηρεάζουν την τελική εμφανίση του σχήματος.
            
             Τα επιστρεφόμενα όρια δεν περικόπτονται στο παραλληλόγραμμο της διαφάνειας.



### Δείτε επίσης
* κλάση [`ZoomFrame`](/slides/python-net/el/aspose.slides/zoomframe)
* κλάση [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)