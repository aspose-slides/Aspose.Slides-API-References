---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/summaryzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος υπολογισμένα από το αποδοθέν περιεχόμενό του.

### Επιστρέφει

Ένα **aspose.slides.RectangleF** που αντιπροσωπεύει τα οπτικά όρια του σχήματος
             σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονα-ευθυγραμμισμένα όρια όλου του περιεχομένου
             που παράγεται από το σχήμα κατά τη διαδικασία απόδοσης στο χώρο συντεταγμένων διαφάνειας.
            
             Αυτά τα όρια μπορεί να διαφέρουν από τα μοντέλα ορίων του σχήματος
             ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
             και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδοθέν περιεχόμενο εκτείνεται
             πέρα από την προέλευση της διαφάνειας.
            
             Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετιζόμενες με την απόδοση όπως
             μετασχηματισμούς (για παράδειγμα, περιστροφή), πλάτος περιγράμματος και ενώσεις,
             διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt, και άλλα εφέ διάταξης
             που επηρεάζουν την τελική εμφανιζόμενη εμφάνιση του σχήματος.
            
             Τα επιστρεφόμενα όρια δεν περικοπούν στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`SummaryZoomFrame`](/slides/python-net/el/aspose.slides/summaryzoomframe)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)