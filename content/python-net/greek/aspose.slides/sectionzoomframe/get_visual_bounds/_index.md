---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/sectionzoomframe/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Αποκτά τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδοθέν περιεχόμενό του.

### Returns
A **aspose.slides.RectangleF** that represents the visual bounds of the shape
             in slide coordinates.

```python
def get_visual_bounds(self):
    ...
```

### Remarks
Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονα-ευθυγραμμισμένα όρια όλων των περιεχομένων που παράγονται από το σχήμα κατά την απόδοση στο χώρο συντεταγμένων διαφάνειας.
            
Αυτά τα όρια μπορεί να διαφέρουν από τα όρια μοντέλου του σχήματος ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y), [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height)) και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδοθέν περιεχόμενο εκτείνεται πέρα από την προέλευση της διαφάνειας.
            
Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετικές με την απόδοση όπως μετασχηματισμούς (π.χ., περιστροφή), πλάτος γραμμής και ενώσεις, διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt και άλλα εφέ διάταξης που επηρεάζουν την τελική εμφανιζόμενη μορφή του σχήματος.
            
Τα επιστρεφθέντα όρια δεν περικόπτονται στο ορθογώνιο της διαφάνειας.

### See Also
* κλάση [`SectionZoomFrame`](/slides/python-net/el/aspose.slides/sectionzoomframe)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)