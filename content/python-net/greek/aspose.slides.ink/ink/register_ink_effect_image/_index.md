---
title: register_ink_effect_image method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
Καταχωρίζει μια εικόνα στη συλλογή προσαρμοσμένων εικόνων που χρησιμοποιούνται για την προσομοίωση οπτικών εφέ για πινέλα μελάνης.
            Αυτές οι εικόνες χρησιμοποιούνται κατά την απόδοση της μελάνης με συγκεκριμένες [`InkEffectType`](/slides/python-net/el/aspose.slides.ink/inkeffecttype) τιμές,
            όπως Galaxy, Rainbow, κλπ. Παρέχοντας τις δικές σας εικόνες, μπορείτε να ελέγξετε πώς εμφανίζεται κάθε εφέ μελάνης.


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/el/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/el/aspose.slides/iimage) |  |

### Παρατηρήσεις

Αυτή η μέθοδος επιτρέπει την αντικατάσταση των προεπιλεγμένων υφών εφέ μελάνης με αυτές που ορίζονται από τον χρήστη,
            κάτι που είναι ιδιαίτερα χρήσιμο όταν τα προεπιλεγμένα στοιχεία περιορίζονται από άδειες ή δεν είναι διαθέσιμα κατά την εκτέλεση.
            Κάθε καταχωρημένο ζεύγος τιμών πρέπει να συσχετίζει μια τιμή [`InkEffectType`](/slides/python-net/el/aspose.slides.ink/inkeffecttype) με ένα αντίστοιχο
            αντικείμενο [`IImage`](/slides/python-net/el/aspose.slides/iimage) (π.χ., Bitmap ή μια διεπαφή εικόνας Aspose).

### Δείτε επίσης
* κλάση [`IImage`](/slides/python-net/el/aspose.slides/iimage)
* κλάση [`Ink`](/slides/python-net/el/aspose.slides.ink/ink)
* απαρίθμηση [`InkEffectType`](/slides/python-net/el/aspose.slides.ink/inkeffecttype)
* μονάδα [`aspose.slides.ink`](/slides/python-net/el/aspose.slides.ink)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)