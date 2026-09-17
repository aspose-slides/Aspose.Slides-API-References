---
title: set_license method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
Δίνει άδεια στο στοιχείο.

```python
def set_license(self, license_name):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| license_name | **str** | Μπορεί να είναι πλήρες ή σύντομο όνομα αρχείου ή όνομα ενσωματωμένου πόρου.<br/><br/> Χρησιμοποιήστε κενή συμβολοσειρά για να μεταβείτε σε λειτουργία αξιολόγησης. |

### Παρατηρήσεις

Προσπαθεί να βρει την άδεια στις παρακάτω θέσεις:

1. Συγκεκριμένη διαδρομή.
2. Ο φάκελος της συναρμολόγησης του στοιχείου.
3. Ο φάκελος της συναρμολόγησης που καλεί ο πελάτης.
4. Ο φάκελος της κύριας συναρμολόγησης.
5. Ένας ενσωματωμένος πόρος στη συναρμολόγηση που καλεί ο πελάτης.

**Σημείωση:** Στο .NET Compact Framework, προσπαθεί να βρει την άδεια μόνο στις ακόλουθες θέσεις:

1. Συγκεκριμένη διαδρομή.
2. Ένας ενσωματωμένος πόρος στη συναρμολόγηση που καλεί ο πελάτης.

## set_license(self, stream) {#iorawiobase}
Δίνει άδεια στο στοιχείο.

```python
def set_license(self, stream):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | **io.RawIOBase** | Μία ροή που περιέχει την άδεια. |

### Παρατηρήσεις

Χρησιμοποιήστε αυτή τη μέθοδο για να φορτώσετε μια άδεια από ροή.

### Δείτε επίσης
* κλάση [`ILicense`](/slides/python-net/el/aspose.slides/ilicense)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)