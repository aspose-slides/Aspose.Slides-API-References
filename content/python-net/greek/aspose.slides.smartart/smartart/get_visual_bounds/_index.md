---
title: get_visual_bounds method
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides.smartart/smartart/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Αντλεί τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδοθέν περιεχόμενό του.

### Επιστρέφει

Ένα **aspose.slides.RectangleF** που αντιπροσωπεύει τα οπτικά όρια του σχήματος
             σε συντεταγμένες διαφάνειας.

```python
def get_visual_bounds(self):
    ...
```

### Παρατηρήσεις

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονα-ευθυγράμματα όρια όλου του περιεχομένου
             που παράγεται από το σχήμα κατά τη διαδικασία απόδοσης στο χώρο συντεταγμένων της διαφάνειας.

Αυτά τα όρια μπορεί να διαφέρουν από τα μοντέλα όρια του σχήματος
             ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
             και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδοθέν περιεχόμενο εκτείνεται πέρα από την αρχή της διαφάνειας.

Τα οπτικά όρια λαμβάνουν υπόψη πτυχές που σχετίζονται με την απόδοση όπως οι μετασχηματισμοί (π.χ., περιστροφή), το πλάτος και οι ενώσεις του περιγράμματος, η διάταξη και η υπερχείλιση κειμένου, η γεωμετρία SmartArt και άλλες επιδράσεις διάταξης
             που επηρεάζουν την τελική αποδοτική εμφάνιση του σχήματος.

Τα επιστρεφόμενα όρια δεν είναι περικομμένα στο ορθογώνιο της διαφάνειας.

### Δείτε επίσης
* κλάση [`SmartArt`](/slides/python-net/el/aspose.slides.smartart/smartart)
* μονάδα [`aspose.slides.smartart`](/slides/python-net/el/aspose.slides.smartart)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)