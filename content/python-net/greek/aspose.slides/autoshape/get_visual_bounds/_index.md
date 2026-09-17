---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/autoshape/get_visual_bounds/
weight: 70
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδομένο περιεχόμενό του.

### Επιστρέφει

A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             Ένα **aspose.slides.RectangleF** που αντιπροσωπεύει τα οπτικά όρια του σχήματος σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονες-ευθυγραμμισμένα όρια όλου του περιεχομένου που παράγεται από το σχήμα κατά την απόδοση στο χώρο συντεταγμένων της διαφάνειας.
            
Αυτά τα όρια μπορεί να διαφέρουν από τα όρια του μοντέλου του σχήματος ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδομένο περιεχόμενο εκτείνεται πέρα από την αρχή της διαφάνειας.
            
Τα οπτικά όρια λαμβάνουν υπόψη τις πτυχές που σχετίζονται με την απόδοση, όπως μετασχηματισμοί (για παράδειγμα, περιστροφή), πάχος και συνδέσεις της γραμμής, διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt, και άλλα εφέ διάταξης που επηρεάζουν την τελική αποδομένη εμφάνιση του σχήματος.
            
Τα επιστρεφόμενα όρια δεν περικόπτονται στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`AutoShape`](/slides/python-net/el/aspose.slides/autoshape)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)