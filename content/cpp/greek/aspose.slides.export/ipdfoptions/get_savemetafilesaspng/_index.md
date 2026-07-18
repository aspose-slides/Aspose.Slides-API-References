---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides για C++ API Reference
description: Αληθές για τη μετατροπή όλων των μετααρχειων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Διαβάστε bool.
type: docs
weight: 287
url: /el/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() μέθοδος

Αληθές για τη μετατροπή όλων των μετααρχειων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Ανάγνωση **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## Παρατηρήσεις

Η προεπιλογή είναι **true**. Το έγγραφο Pdf μπορεί να περιέχει διανυσματικά γραφικά και raster εικόνες. Εάν το SaveMetafilesAsPng οριστεί σε true, τότε η εικόνα source Metafile μετατρέπεται σε μορφή Png και αποθηκεύεται στο Pdf ως raster εικόνα. Εάν το SaveMetafilesAsPng οριστεί σε false, τότε το source Metafile μετατρέπεται σε διανυσματικά γραφικά Pdf. Κάθε προσέγγιση έχει πλεονεκτήματα και μειονεκτήματα. Για παράδειγμα, εάν το Metafile μετατραπεί σε PNG, τότε μπορεί να προκύψει κάποια απώλεια ποιότητας κατά την κλιμάκωση του τελικού εγγράφου. Εάν το Metafile μετατραπεί σε διανυσματικά γραφικά Pdf, τότε είναι δυνατά προβλήματα απόδοσης στο εργαλείο προβολής Pdf.

## Δείτε επίσης

* Κλάση [IPdfOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)