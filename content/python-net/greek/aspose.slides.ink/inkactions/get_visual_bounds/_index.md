---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Αποκτά τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδοθέν περιεχόμενο.

### Επιστρέφει

Ένα [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef) που αντιπροσωπεύει τα οπτικά όρια του σχήματος
             σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις
Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα ευθυγραμμισμένα ως προς άξονα όρια όλου του περιεχομένου
             που παράγονται από το σχήμα κατά την απόδοση στον χώρο συντεταγμένων της διαφάνειας.

Αυτά τα όρια μπορεί να διαφέρουν από τα όρια του μοντέλου του σχήματος
             ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδοθέν περιεχόμενο επεκτείνεται
             πέρα από την αρχή της διαφάνειας.

Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετικές με την απόδοση όπως
             μετασχηματισμοί (π.χ., περιστροφή), πλάτος περιγράμματος και συνδέσεις,
             διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt, και άλλες επιδράσεις διάταξης
που επηρεάζουν την τελική εμφάνιση του σχήματος μετά την απόδοση.

Τα επιστρεφόμενα όρια δεν κόβονται στον ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`InkActions`](/slides/python-net/el/aspose.slides.ink/inkactions)
* κλάση [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef)
* μονάδα [`aspose.slides.ink`](/slides/python-net/el/aspose.slides.ink)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)