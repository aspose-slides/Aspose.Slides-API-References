---
title: save_metafiles_as_png property
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.export/ipdfoptions/save_metafiles_as_png/
weight: 190
---
## save_metafiles_as_png ιδιότητα
True για μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG.
Ανάγνωση/εγγραφή **bool**.

### Σχόλια

Η προεπιλογή είναι **true** .
Έγγραφο Pdf μπορεί να περιέχει διανυσματικά γραφικά και ραστρικές εικόνες. 
Αν το SaveMetafilesAsPng οριστεί σε true, τότε η πηγή Metafile εικόνα μετατρέπεται σε μορφή Png και αποθηκεύεται στο Pdf ως ραστρική εικόνα. 
Αν το SaveMetafilesAsPng οριστεί σε false, τότε η πηγή Metafile μετατρέπεται σε διανυσματικά γραφικά Pdf. 
Κάθε προσέγγιση έχει πλεονεκτήματα και μειονεκτήματα. 
Για παράδειγμα, εάν το Metafile μετατραπεί σε PNG, τότε είναι πιθανή κάποια απώλεια ποιότητας κατά την κλιμάκωση του τελικού εγγράφου. 
Εάν το Metafile μετατραπεί σε διανυσματικά γραφικά Pdf, τότε είναι πιθανά προβλήματα απόδοσης στο εργαλείο προβολής Pdf.

### Ορισμός:
```python
@property
def save_metafiles_as_png(self):
    ...

@save_metafiles_as_png.setter
def save_metafiles_as_png(self, value):
    ...
```

### Δείτε επίσης
* κλάση [`IPdfOptions`](/slides/python-net/el/aspose.slides.export/ipdfoptions)
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)