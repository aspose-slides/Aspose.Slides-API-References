---
title: from_known_color method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/color/from_known_color/
weight: 30
---
## from_known_color(known_color) {#knowncolor}
Δημιουργεί ένα χρώμα από το καθορισμένο προεπιλεγμένο χρώμα.<br/>Αυτή είναι η μοναδική μέθοδος για την απόκτηση ενός χρώματος συστήματος (όπως `KnownColor.CONTROL`): τα χρώματα συστήματος δεν εκτίθενται ως χαρακτηριστικά `Color` επειδή οι τιμές τους εξαρτώνται από το θέμα της επιφάνειας εργασίας, έτσι διαβάζονται από το runtime της βιβλιοθήκης.

### Επιστρέφει

Το χρώμα που δημιουργεί αυτή η μέθοδος.



```python
@staticmethod
def from_known_color(known_color):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| known_color | **KnownColor** | Ένα στοιχείο της αρίθμησης `KnownColor` (ένα `IntEnum` που αντικατοπτρίζει το .NET `System.Drawing.KnownColor`) ή η ακέραια τιμή του. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **ValueError** | Η τιμή δεν είναι έγκυρο μέλος του `KnownColor`. |



### Δείτε επίσης
* κλάση [`Color`](/slides/python-net/el/aspose.slides/color)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)