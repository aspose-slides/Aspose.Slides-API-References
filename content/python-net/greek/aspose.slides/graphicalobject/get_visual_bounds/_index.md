---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/graphicalobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδοθέν περιεχόμενό του.

### Επιστρέφει

Ένα [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef) που αντιπροσωπεύει τα οπτικά όρια του σχήματος σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονες ευθυγραμμισμένα όρια όλου του περιεχομένου που παράγεται από το σχήμα κατά την απόδοση στον χώρο συντεταγμένων της διαφάνειας.

Αυτά τα όρια μπορεί να διαφέρουν από τα όρια του μοντέλου του σχήματος ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height)) και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδοθέν περιεχόμενο εκτείνεται πέρα από την αρχή της διαφάνειας.

Τα οπτικά όρια λαμβάνουν υπόψη τις πτυχές που σχετίζονται με την απόδοση, όπως οι μετασχηματισμοί (π.χ., περιστροφή), το πάχος των γραμμών και οι ενώσεις, η διάταξη κειμένου και η υπερχείλιση, η γεωμετρία SmartArt και άλλα εφέ διάταξης που επηρεάζουν την τελική εμφάνιση του σχήματος.

Τα επιστρεφόμενα όρια δεν περικόπτονται στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`GraphicalObject`](/slides/python-net/el/aspose.slides/graphicalobject)
* κλάση [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)