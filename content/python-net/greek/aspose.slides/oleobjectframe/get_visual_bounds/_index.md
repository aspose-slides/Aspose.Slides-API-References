---
title: get_visual_bounds method
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides/oleobjectframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Αποκτά τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδιδόμενο περιεχόμενό του.

### Επιστρέφει

Ένα **aspose.slides.RectangleF** που αντιπροσωπεύει τα οπτικά όρια του σχήματος
             σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Παρατηρήσεις

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα ευθυγραμμισμένα κατά άξονες όρια όλου του περιεχομένου που παράγεται από το σχήμα κατά τη διάρκεια της απόδοσης στο χώρο συντεταγμένων της διαφάνειας.

Αυτά τα όρια μπορεί να διαφέρουν από τα όρια του μοντέλου του σχήματος ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height)) και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδιδόμενο περιεχόμενο εκτείνεται πέρα από την αρχή της διαφάνειας.

Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετικές με την απόδοση όπως μετασχηματισμούς (π.χ., περιστροφή), το πλάτος και τις ενώσεις της γραμμής, τη διάταξη και την υπερχείλιση κειμένου, τη γεωμετρία SmartArt, και άλλες επιδράσεις διάταξης που επηρεάζουν την τελική αποδιδόμενη εμφάνιση του σχήματος.

Τα επιστρεφόμενα όρια δεν περικοπούν στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`OleObjectFrame`](/slides/python-net/el/aspose.slides/oleobjectframe)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)