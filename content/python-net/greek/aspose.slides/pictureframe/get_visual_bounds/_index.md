---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Ανακτά τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδομένο περιεχόμενο.

### Επιστρέφει

Ένα **aspose.slides.RectangleF** που αντιπροσωπεύει τα οπτικά όρια του σχήματος σε συντεταγμένες διαφάνειας.

```python
def get_visual_bounds(self):
    ...
```

### Παρατηρήσεις

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονες-ευθυγράμμιτα όρια όλου του περιεχομένου που παράγεται από το σχήμα κατά τη διαδικασία απόδοσης στο χώρο συντεταγμένων της διαφάνειας.

Αυτά τα όρια μπορεί να διαφέρουν από τα μοντέλα ορίων του σχήματος ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height)) και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδομένο περιεχόμενο εκτείνεται πέρα από την αρχή της διαφάνειας.

Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετικές με την απόδοση, όπως μετασχηματισμοί (π.χ., περιστροφή), πλάτος και ενώσεις περιγράμματος, διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt, και άλλες επιδράσεις διάταξης που επηρεάζουν την τελική αποδομένη εμφάνιση του σχήματος.

Τα επιστρεφόμενα όρια δεν περικόπτονται στο ορθογώνιο της διαφάνειας.

### Δείτε επίσης
* κλάση [`PictureFrame`](/slides/python-net/el/aspose.slides/pictureframe)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)