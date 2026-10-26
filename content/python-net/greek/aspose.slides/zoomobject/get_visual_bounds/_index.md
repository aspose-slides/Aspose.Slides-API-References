---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδιδόμενο περιεχόμενό του.

### Επιστρέφει

Ένα [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef) που αντιπροσωπεύει τα οπτικά όρια του σχήματος
             σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονες-ευθυγραμμισμένα όρια όλου του περιεχομένου που παράγεται από το σχήμα κατά τη διάρκεια της απόδοσης στο χώρο συντεταγμένων της διαφάνειας.
            
Αυτά τα όρια μπορεί να διαφέρουν από τα μοντέλα όρια του σχήματος
 ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
 [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
 και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδιδόμενο περιεχόμενο επεκτείνεται πέρα από το αρχικό σημείο της διαφάνειας.
            
Τα οπτικά όρια λαμβάνουν υπόψη πτυχές που σχετίζονται με την απόδοση, όπως οι μετασχηματισμοί (για παράδειγμα, περιστροφή), το πλάτος και οι συγκολλήσεις του περιγράμματος, η διάταξη και η υπερχείλιση του κειμένου, η γεωμετρία του SmartArt, και άλλα εφέ διάταξης που επηρεάζουν την τελική εμφανιζόμενη εμφάνιση του σχήματος.
            
Τα επιστρεφόμενα όρια δεν έχουν περικοπεί στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`ZoomObject`](/slides/python-net/el/aspose.slides/zoomobject)
* κλάση [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)