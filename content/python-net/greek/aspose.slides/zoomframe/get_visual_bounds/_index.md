---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/zoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Λαβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδιδόμενο περιεχόμενό του.

### Επιστρέφει

A **aspose.slides.RectangleF** που αντιπροσωπεύει τα οπτικά όρια του σχήματος
             σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις
Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονα-ευθυγραμμένα όρια όλου του περιεχομένου
             που παράγεται από το σχήμα κατά τη διάρκεια της απόδοσης στο χώρο
             συντεταγμένων της διαφάνειας.
             
             Αυτά τα όρια μπορεί να διαφέρουν από τα όρια του μοντέλου του σχήματος
             ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
             και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδιδόμενο περιεχόμενο
             εκτείνεται πέρα από την αρχή της διαφάνειας.
             
             Τα οπτικά όρια λαμβάνουν υπόψη πλευρές που σχετίζονται με την απόδοση,
             όπως μετασχηματισμούς (π.χ., περιστροφή), το πάχος και τις ενώσεις της
             γραμμής, τη διάταξη και την υπερχείλιση του κειμένου, τη γεωμετρία του
             SmartArt και άλλα εφέ διάταξης που επηρεάζουν την τελική εμφάνιση του
             σχήματος.
             
             Τα επιστρεφόμενα όρια δεν περικόπτονται στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`ZoomFrame`](/slides/python-net/el/aspose.slides/zoomframe)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)