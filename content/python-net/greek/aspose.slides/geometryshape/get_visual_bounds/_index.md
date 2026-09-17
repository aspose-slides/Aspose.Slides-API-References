---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδοσμένο του περιεχόμενο.

### Returns

Ένα **aspose.slides.RectangleF** που αντιπροσωπεύει τα οπτικά όρια του σχήματος σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονες ευθυγραμμισμένα όρια όλου του περιεχομένου που παράγεται από το σχήμα κατά τη διάρκεια της απόδοσης στο χώρο των συντεταγμένων της διαφάνειας.

Τα όρια μπορεί να διαφέρουν από τα μοντέλα ορίων του σχήματος ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height)) και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδοσμένο περιεχόμενο εκτείνεται πέρα από την αρχή της διαφάνειας.

Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετικές με την απόδοση όπως μετασχηματισμούς (π.χ., περιστροφή), πλάτος και ενώσεις του περιγράμματος, διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt, και άλλα εφέ διάταξης που επηρεάζουν την τελική εμφάνιση του σχήματος.

Τα επιστρεφόμενα όρια δεν περικοπούν στο ορθογώνιο της διαφάνειας.



### See Also
* κλάση [`GeometryShape`](/slides/python-net/el/aspose.slides/geometryshape)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)