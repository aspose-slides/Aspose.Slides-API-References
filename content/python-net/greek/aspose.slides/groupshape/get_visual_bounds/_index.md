---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/groupshape/get_visual_bounds/
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


### Σχόλια
Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονα-ευθυγραμμισμένα όρια όλου του περιεχομένου που παράγεται από το σχήμα κατά την απόδοση στο χώρο συντεταγμένων διαφάνειας.
             Αυτά τα όρια μπορεί να διαφέρουν από τα όρια μοντέλου του σχήματος
             ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
             και μπορεί να περιέχει αρνητικές συντεταγμένες εάν το αποδοθέν περιεχόμενο εκτείνεται
             πέρα από την αρχή της διαφάνειας.
Τα οπτικά όρια λαμβάνουν υπόψη τις πτυχές που σχετίζονται με την απόδοση, όπως
             μετασχηματισμοί (για παράδειγμα, περιστροφή), πλάτος περιγράμματος και ενώσεις,
             διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt, και άλλες επιδράσεις διάταξης
             που επηρεάζουν την τελική αποδομένη εμφάνιση του σχήματος.
Τα επιστρεφόμενα όρια δεν περικόπτονται στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`GroupShape`](/slides/python-net/el/aspose.slides/groupshape)
* κλάση [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)