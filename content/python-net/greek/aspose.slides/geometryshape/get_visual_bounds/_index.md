---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/geometryshape/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδιδόμενο περιεχόμενο.

### Επιστρέφει

Ένα [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef) που αντιπροσωπεύει τα οπτικά όρια του σχήματος σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα ευθυγραμμισμένα ως προς τους άξονες όρια όλου του περιεχομένου
             που παράγονται από το σχήμα κατά τη διάρκεια της απόδοσης στον χώρο συντεταγμένων της διαφάνειας.

Αυτά τα όρια μπορεί να διαφέρουν από τα μοντέλα όρια του σχήματος
             ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
             και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδεδιδόμενο περιεχόμενο εκτείνεται πέρα από την αρχή της διαφάνειας.

Τα οπτικά όρια λαμβάνουν υπόψη τις πτυχές σχετικές με την απόδοση, όπως
             μετασχηματισμοί (για παράδειγμα, περιστροφή), πλάτος γραμμής και ένωση,
             διάταξη κειμένου και υπέρβαση, γεωμετρία SmartArt, και άλλες επιδράσεις διάταξης
             που επηρεάζουν την τελική εμφάνιση του σχήματος μετά την απόδοση.

Τα επιστρεφόμενα όρια δεν περικοπώνται στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`GeometryShape`](/slides/python-net/el/aspose.slides/geometryshape)
* κλάση [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)