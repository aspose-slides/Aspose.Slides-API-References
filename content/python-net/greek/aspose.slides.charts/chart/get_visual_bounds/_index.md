---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/chart/get_visual_bounds/
weight: 50
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδιδόμενο περιεχόμενού του.

### Επιστρέφει

Ένα **aspose.slides.RectangleF** που αντιπροσωπεύει τα οπτικά όρια του σχήματος σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Σχόλια

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονα-ευθυγραμμισμένα όρια όλων του περιεχομένου
που παράγεται από το σχήμα κατά τη διάρκεια της απόδοσης στο χώρο συντεταγμένων της διαφάνειας.

Αυτά τα όρια μπορεί να διαφέρουν από τα όρια μοντέλου του σχήματος
([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
[`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
και μπορεί να περιέχουν αρνητικές συντεταγμένες εάν το αποδιδόμενο περιεχόμενο εκτείνεται
πέρα από την αρχή της διαφάνειας.

Τα οπτικά όρια λαμβάνουν υπόψη πτυχές σχετικές με την απόδοση, όπως
μετασχηματισμοί (για παράδειγμα, περιστροφή), πλάτος πινελιάς και σύνδεσμοι,
διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt, και άλλα εφέ διάταξης
που επηρεάζουν την τελική αποδιδόμενη εμφάνιση του σχήματος.

Τα επιστρεφόμενα όρια δεν περικόπτονται στο ορθογώνιο της διαφάνειας.



### Δείτε επίσης
* κλάση [`Chart`](/slides/python-net/el/aspose.slides.charts/chart)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)