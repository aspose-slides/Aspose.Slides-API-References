---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/pictureframe/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος υπολογισμένα από το αποδοθέν περιεχόμενό του.

### Επιστρέφει
Ένα [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef) που αντιπροσωπεύει τα οπτικά όρια του σχήματος σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Σημειώσεις
Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα με άξονες ευθυγραμμισμένα όρια όλου του περιεχομένου που παράγεται από το σχήμα κατά τη διάρκεια απόδοσης στον χώρο συντεταγμένων διαφάνειας.

Αυτά τα όρια μπορεί να διαφέρουν από τα όρια του μοντέλου του σχήματος ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height)) και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδοθέν περιεχόμενο εκτείνεται πέρα από την αρχή της διαφάνειας.

Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετικές με την απόδοση, όπως μετασχηματισμούς (για παράδειγμα, στροφή), πλάτος γραμμής και συνδέσεις, διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt και άλλα εφέ διάταξης που επηρεάζουν την τελική εμφάνιση του σχήματος.

Τα επιστρεφόμενα όρια δεν περικοπούν στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`PictureFrame`](/slides/python-net/el/aspose.slides/pictureframe)
* κλάση [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)