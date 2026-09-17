---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδοθέν περιεχόμενό του.

### Επιστρέφει

Ένα **aspose.slides.RectangleF** που αντιπροσωπεύει τα οπτικά όρια του σχήματος σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονα-ευθυγραμμισμένα όρια όλου του περιεχομένου που παράγεται από το σχήμα κατά τη διάρκεια της απόδοσης στο χώρο συντεταγμένων της διαφάνειας.

Αυτά τα όρια ενδέχεται να διαφέρουν από τα όρια μοντέλου του σχήματος ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height)) και να περιέχουν αρνητικές συντεταγμένες αν το αποδοθέν περιεχόμενο εκτείνεται πέρα από την αρχή της διαφάνειας.

Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετικές με την απόδοση, όπως μετασχηματισμούς (π.χ., περιστροφή), το πλάτος και τις ενώσεις του περιγράμματος, τη διάταξη κειμένου και την υπερχείλιση, τη γεωμετρία SmartArt, και άλλα εφέ διάταξης που επηρεάζουν την τελική εμφανιζόμενη μορφή του σχήματος.

Τα επιστρεφόμενα όρια δεν κόβονται στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`SummaryZoomSection`](/slides/python-net/el/aspose.slides/summaryzoomsection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)