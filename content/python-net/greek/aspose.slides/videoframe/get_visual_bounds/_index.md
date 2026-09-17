---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET αναφορά API
description: 
type: docs
url: /el/aspose.slides/videoframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδιδόμενο περιεχόμενο.

### Επιστρέφει

Ένα **aspose.slides.RectangleF** που αντιπροσωπεύει τα οπτικά όρια του σχήματος
             σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα αξονικά ευθυγραμμισμένα όρια όλου του περιεχομένου
 που παράγεται από το σχήμα κατά τη διαδικασία απόδοσης στο χώρο των συντεταγμένων της διαφάνειας.
            
Αυτά τα όρια μπορεί να διαφέρουν από τα όρια του μοντέλου του σχήματος
 ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
 [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
 και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδιδόμενο περιεχόμενο εκτείνεται
 πέρα από την αρχή της διαφάνειας.
            
Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετικές με την απόδοση όπως
 οι μετασχηματισμούς (για παράδειγμα, περιστροφή), το πάχος και τις ενώσεις του περιγράμματος,
 τη διάταξη και υπερχείλιση κειμένου, τη γεωμετρία SmartArt, και άλλες επιδράσεις διάταξης
 που επηρεάζουν την τελική εμφάνιση του σχήματος μετά την απόδοση.
            
Τα επιστρεφόμενα όρια δεν περικοπώνται στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`VideoFrame`](/slides/python-net/el/aspose.slides/videoframe)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)