---
title: get_visual_bounds method
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides/connector/get_visual_bounds/
weight: 60
---
## get_visual_bounds(self) {#}
Επιστρέφει τα οπτικά όρια του σχήματος που υπολογίζονται από το εμφανιζόμενο περιεχόμενό του.

### Returns

Ένα **aspose.slides.RectangleF** που αντιπροσωπεύει τα οπτικά όρια του σχήματος
             σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονα-ευθυγραμμισμένα όρια όλου του περιεχομένου
             που παράγεται από το σχήμα κατά τη διάρκεια της απόδοσης στον χώρο συντεταγμένων της διαφάνειας.

Αυτά τα όρια μπορεί να διαφέρουν από τα μοντέλα ορίων του σχήματος
             ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y), 
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
             και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το εμφανιζόμενο περιεχόμενο επεκτείνεται
             πέρα από την αρχή της διαφάνειας.

Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετικές με την απόδοση, όπως
             μετασχηματισμούς (για παράδειγμα, περιστροφή), πλάτος περιγράμματος και συνδέσεις,
             διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt, και άλλα εφέ διάταξης
             που επηρεάζουν την τελική εμφανιζόμενη εμφάνιση του σχήματος.

Τα επιστρεφόμενα όρια δεν είναι περικομμένα στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`Connector`](/slides/python-net/el/aspose.slides/connector)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)