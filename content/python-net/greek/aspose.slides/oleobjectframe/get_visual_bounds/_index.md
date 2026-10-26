---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδομένο του περιεχόμενο.

### Επιστρέφει

Ένα [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef) που αντιπροσωπεύει τα οπτικά όρια του σχήματος
             σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα οριοθετημένα κατά άξονα όρια όλου του
             περιεχομένου που παράγεται από το σχήμα κατά την απόδοση στο χώρο
             συντεταγμένων της διαφάνειας.
            
             Αυτά τα όρια μπορεί να διαφέρουν από τα μοντέλα ορίσματα του σχήματος
             ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
             και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδομένο
             περιεχόμενο εκτείνεται πέρα από την αρχή της διαφάνειας.
            
             Τα οπτικά όρια λαμβάνουν υπόψη τις πτυχές που σχετίζονται με την
             απόδοση, όπως οι μετασχηματισμοί (για παράδειγμα, περιστροφή), το
             πλάτος και οι συνδέσεις του περιγράμματος, η διάταξη και η
             υπερχείλιση του κειμένου, η γεωμετρία SmartArt, και άλλες
             επιδράσεις διάταξης που επηρεάζουν την τελική αποδομένη εμφάνιση
             του σχήματος.
            
             Τα επιστρεφόμενα όρια δεν περικοπούν στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`OleObjectFrame`](/slides/python-net/el/aspose.slides/oleobjectframe)
* κλάση [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)