---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.ink/inkactions/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το εμφανιζόμενο περιεχόμενό του.

### Επιστρέφει

Ένα **aspose.slides.RectangleF** που αντιπροσωπεύει τα οπτικά όρια του σχήματος σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονα-ευθυγραμμισμένα όρια όλων των περιεχομένων που παράγονται από το σχήμα κατά τη διάρκεια της απόδοσης στο χώρο συντεταγμένων της διαφάνειας.

Αυτά τα όρια μπορεί να διαφέρουν από τα μοντέλα ορίων του σχήματος ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height)) και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το εμφανιζόμενο περιεχόμενο επεκτείνεται πέρα από την αρχή της διαφάνειας.

Τα οπτικά όρια λαμβάνουν υπόψη στοιχεία που σχετίζονται με την απόδοση όπως μετασχηματισμούς (π.χ., περιστροφή), το πλάτος και τις ενώσεις της γραμμής, τη διάταξη και υπερχείλισμα κειμένου, τη γεωμετρία SmartArt και άλλες επιδράσεις διάταξης που επηρεάζουν την τελική εμφάνιση του σχήματος.

Τα επιστρεφόμενα όρια δεν περικόπτονται στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`InkActions`](/slides/python-net/el/aspose.slides.ink/inkactions)
* μονάδα [`aspose.slides.ink`](/slides/python-net/el/aspose.slides.ink)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)