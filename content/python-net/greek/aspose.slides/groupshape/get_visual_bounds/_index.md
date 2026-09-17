---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/groupshape/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Επιστρέφει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδοθέν περιεχόμενό του.

### Επιστρέφει

Ένα **aspose.slides.RectangleF** που αντιπροσωπεύει τα οπτικά όρια του σχήματος σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις
Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονα-ευθυγραμμισμένα όρια όλων των περιεχομένων
             που παράγονται από το σχήμα κατά τη διαδικασία απόδοσης στο χώρο συντεταγμένων της διαφάνειας.

Αυτά τα όρια ενδέχεται να διαφέρουν από τα όρια του μοντέλου του σχήματος
             ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
             και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδοθέν περιεχόμενο εκτείνεται
             πέρα από το σημείο προέλευσης της διαφάνειας.

Τα οπτικά όρια λαμβάνουν υπόψη τα στοιχεία που σχετίζονται με την απόδοση, όπως
             μετασχηματισμούς (για παράδειγμα, περιστροφή), πλάτος γραμμής και ενώσεις,
             διάταξη κειμένου και υπερχείλιση, SmartArt γεωμετρία, και άλλα εφέ διάταξης
             που επηρεάζουν την τελική εμφάνιση του σχήματος μετά την απόδοση.

Τα επιστρεφόμενα όρια δεν περικόπτονται στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`GroupShape`](/slides/python-net/el/aspose.slides/groupshape)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)