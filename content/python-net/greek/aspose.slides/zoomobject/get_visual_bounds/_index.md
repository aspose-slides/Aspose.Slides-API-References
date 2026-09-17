---
title: get_visual_bounds method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/zoomobject/get_visual_bounds/
weight: 40
---
## get_visual_bounds(self) {#}
Λαμβάνει τα οπτικά όρια του σχήματος που υπολογίζονται από το αποδοθέν περιεχόμενό του.

### Returns

Ένα **aspose.slides.RectangleF** που αντιπροσωπεύει τα οπτικά όρια του σχήματος
             σε συντεταγμένες διαφάνειας.



```python
def get_visual_bounds(self):
    ...
```


### Remarks

Το επιστρεφόμενο ορθογώνιο αντιπροσωπεύει τα άξονες-ευθυγραμμισμένα όρια όλων του περιεχομένου
             που παράγεται από το σχήμα κατά την απόδοση στον χώρο συντεταγμένων της διαφάνειας.
            
             Αυτά τα όρια μπορεί να διαφέρουν από τα μοντέλα-όρια του σχήματος
             ([`Shape.x`](/slides/python-net/el/aspose.slides/shape/x), [`Shape.y`](/slides/python-net/el/aspose.slides/shape/y),
             [`Shape.width`](/slides/python-net/el/aspose.slides/shape/width), [`Shape.height`](/slides/python-net/el/aspose.slides/shape/height))
             και μπορεί να περιλαμβάνουν αρνητικές συντεταγμένες εάν το αποδοθέν περιεχόμενο εκτείνεται
             πέρα από την αρχή της διαφάνειας.
            
             Τα οπτικά όρια λαμβάνουν υπόψη πτυχές που σχετίζονται με την απόδοση όπως
             μετασχηματισμοί (για παράδειγμα, περιστροφή), πλάτος περιγράμματος και σύνδεσμοι,
             διάταξη κειμένου και υπερχείλιση, γεωμετρία SmartArt και άλλες επιδράσεις διάταξης
             που επηρεάζουν την τελική αποδοθή μορφή του σχήματος.
            
             Τα επιστρεφόμενα όρια δεν περικόπτονται στο ορθογώνιο της διαφάνειας.



### See Also
* κλάση [`ZoomObject`](/slides/python-net/el/aspose.slides/zoomobject)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)