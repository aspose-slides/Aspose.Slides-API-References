---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/table/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδιδόμενο περιεχόμενό του.

### Επιστρέφει

Ένα [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef) που αντιπροσωπεύει τα οπτικά όρια του σχήματος σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα αδιατάσσητα όρια όλων των περιεχομένων
             που παράγονται από το σχήμα κατά την απόδοση στο χώρο συντεταγμένων της διαφάνειας.
            
             Αυτά τα όρια μπορεί να διαφέρουν από τα όρια μοντέλου του σχήματος
             ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
             και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδιδόμενο περιεχόμενο εκτείνεται
             πέρα από την αρχή της διαφάνειας.
            
             Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετικές με την απόδοση όπως
             μετασχηματισμούς (για παράδειγμα, περιστροφή), πλάτος και ενώσεις πινέλου,
             διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt, και άλλες επιδράσεις διάταξης
             που επηρεάζουν την τελική αποδιδόμενη εμφάνιση του σχήματος.
            
             Τα επιστρεφόμενα όρια δεν περικόπτονται στο ορθογώνιο της διαφάνειας.

### Δείτε επίσης
* κλάση [`Table`](/slides/python-net/el/aspose.slides/table)
* κλάση [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)