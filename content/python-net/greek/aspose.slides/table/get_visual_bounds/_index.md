---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποτυπωμένο του περιεχόμενο.

### Επιστροφή

Ένα **aspose.slides.RectangleF** που αντιπροσωπεύει τα οπτικά όρια του σχήματος
             σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονες-ευθυγράμμιτα όρια όλου του περιεχομένου
             που παράγεται από το σχήμα κατά την απόδοση στο χώρο συντεταγμένων διαφάνειας.
            
             Αυτά τα όρια μπορεί να διαφέρουν από τα μοντέλα ορίων του σχήματος
             ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
             και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποτυπωμένο περιεχόμενο εκτείνεται
             πέρα από την αρχή της διαφάνειας.
            
             Τα οπτικά όρια λαμβάνουν υπόψη τις πτυχές που σχετίζονται με την απόδοση όπως
             μετασχηματισμοί (για παράδειγμα, περιστροφή), πάχος και ενώσεις γραμμής,
             διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt, και άλλα εφέ διάταξης
             που επηρεάζουν την τελική αποτυπωμένη εμφάνιση του σχήματος.
            
             Τα επιστρεφόμενα όρια δεν κόβονται στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`Table`](/slides/python-net/el/aspose.slides/table)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)