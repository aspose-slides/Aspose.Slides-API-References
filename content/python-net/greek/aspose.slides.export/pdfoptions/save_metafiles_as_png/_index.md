---
title: save_metafiles_as_png property
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.export/pdfoptions/save_metafiles_as_png/
weight: 200
---
## save_metafiles_as_png ιδιότητα
True to convert all metafiles used in a presentation to the PNG images.
            Ανάγνωση/εγγραφή **bool**.

### Σχόλια

Η προεπιλογή είναι **true** .
            Το έγγραφο Pdf μπορεί να περιέχει διανυσματικά γραφικά και ραστερ εικόνες. 
            Αν το SaveMetafilesAsPng οριστεί σε true, τότε η εικόνα Metafile πηγής μετατρέπεται σε μορφή Png και αποθηκεύεται στο Pdf ως ραστερ εικόνα. 
            Αν το SaveMetafilesAsPng οριστεί σε false, τότε η πηγή Metafile μετατρέπεται σε διανυσματικά γραφικά Pdf. 
            Κάθε προσέγγιση έχει πλεονεκτήματα και μειονεκτήματα. 
            Για παράδειγμα, αν το Metafile μετατραπεί σε PNG, τότε είναι δυνατόν να προκύψει απώλεια ποιότητας κατά την κλιμάτωση του προκύπτοντος εγγράφου. 
            Αν το Metafile μετατραπεί σε διανυσματικά γραφικά Pdf, τότε είναι δυνατόν να προκύψουν προβλήματα απόδοσης στο εργαλείο προβολής Pdf.

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
* κλάση [`PdfOptions`](/slides/python-net/el/aspose.slides.export/pdfoptions)
* μονάδα [`aspose.slides.export`](/slides/python-net/el/aspose.slides.export)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)