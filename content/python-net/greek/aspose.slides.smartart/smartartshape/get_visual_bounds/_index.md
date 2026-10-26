---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.smartart/smartartshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποτυπωμένο του περιεχόμενο.

### Επιστρέφει

Ένα [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef) που αντιπροσωπεύει τα οπτικά όρια του σχήματος
             σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Σχόλια

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονα-ευθυγραμμισμένα όρια όλου του περιεχομένου
             που παράγεται από το σχήμα κατά τη διάρκεια της απόδοσης στο χώρο συντεταγμένων της διαφάνειας.
            
             Αυτά τα όρια ενδέχεται να διαφέρουν από τα μοντέλο όρια του σχήματος
             ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
             και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποτυπωμένο περιεχόμενο εκτείνεται πέρα από την αρχή της διαφάνειας.
            
             Τα οπτικά όρια λαμβάνουν υπόψη στοιχεία σχετιζόμενα με την απόδοση όπως μετασχηματισμοί (για παράδειγμα, περιστροφή), πλάτος γραμμής και συνδέσεις,
             διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt, και άλλα εφέ διάταξης που επηρεάζουν την τελική εμφάνιση της αποδοθείσας μορφής του σχήματος.
            
             Τα επιστρεφόμενα όρια δεν είναι περικομμένα στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`SmartArtShape`](/slides/python-net/el/aspose.slides.smartart/smartartshape)
* κλάση [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef)
* μονάδα [`aspose.slides.smartart`](/slides/python-net/el/aspose.slides.smartart)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)