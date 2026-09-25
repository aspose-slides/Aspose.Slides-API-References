---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/summaryzoomsection/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Αποκτά τα οπτικά όρια του σχήματος, υπολογισμένα από το αποδιδόμενο περιεχόμενό του.

### Επιστρέφει

Ένα [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef) που αντιπροσωπεύει τα οπτικά όρια του σχήματος σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις

             Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονα-ευθυγραμμισμένα όρια όλου του περιεχομένου που παράγεται από το σχήμα κατά τη διαδικασία απόδοσης στο χώρο συντεταγμένων της διαφάνειας.

             Αυτά τα όρια μπορεί να διαφέρουν από τα όρια του μοντέλου του σχήματος ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height)) και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδιδόμενο περιεχόμενο εκτείνεται πέρα από την αρχή της διαφάνειας.

             Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετικές με την απόδοση όπως οι μετασχηματισμοί (π.χ., περιστροφή), το πάχος και οι ενώσεις της γραμμής, η διάταξη κειμένου και η υπερχείλιση, η γεωμετρία SmartArt και άλλες επιδράσεις διάταξης που επηρεάζουν την τελική εμφάνιση του σχήματος μετά την απόδοση.

             Τα επιστρεφόμενα όρια δεν περικόπτονται στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`SummaryZoomSection`](/slides/python-net/el/aspose.slides/summaryzoomsection)
* κλάση [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)