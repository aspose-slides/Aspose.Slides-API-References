---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/legacydiagram/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Αποκτά τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδομένο περιεχόμενό του.

### Επιστρέφει

Ένα [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef) που αντιπροσωπεύει τα οπτικά όρια του σχήματος
             σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Σχόλια

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονα-ευθυγραμμισμένα όρια όλου του περιεχομένου
             που παράγεται από το σχήμα κατά τη διάρκεια της απόδοσης στο χώρο συντεταγμένων διαφάνειας.
            
             Αυτά τα όρια μπορεί να διαφέρουν από τα όρια μοντέλου του σχήματος
             ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
             και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδομένο περιεχόμενο επεκτείνεται
             πέρα από την αρχή της διαφάνειας.
            
             Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετιζόμενες με την απόδοση όπως
             μετασχηματισμοί (για παράδειγμα, περιστροφή), πλάτος γραμμής και ενώσεις,
             διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt, και άλλα εφέ διάταξης
             που επηρεάζουν την τελική εμφάνιση του σχήματος μετά την απόδοση.
            
             Τα επιστρεφόμενα όρια δεν περικόπτονται στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`LegacyDiagram`](/slides/python-net/el/aspose.slides/legacydiagram)
* κλάση [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)