---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides για C++ API Αναφορά
description: True για τη μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Read bool.
type: docs
weight: 326
url: /el/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() μέθοδος

True για τη μετατροπή όλων των μετααρχείων που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Ανάγνωση **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## Παρατηρήσεις

Η προεπιλογή είναι **true**. Το έγγραφο Pdf μπορεί να περιέχει διανυσματικά γραφικά και εικόνες raster. Αν το SaveMetafilesAsPng είναι ορισμένο σε true, τότε η πηγή Metafile εικόνα μετατρέπεται σε μορφή Png και αποθηκεύεται στο Pdf ως εικόνα raster. Αν το SaveMetafilesAsPng είναι ορισμένο σε false, τότε η πηγή Metafile μετατρέπεται σε διανυσματικά γραφικά Pdf. Κάθε προσέγγιση έχει πλεονεκτήματα και μειονεκτήματα. Για παράδειγμα, εάν το Metafile μετατραπεί σε PNG, τότε είναι δυνατόν να υπάρξει κάποια απώλεια ποιότητας κατά την κλιμάκωση του τελικού εγγράφου. Αν το Metafile μετατραπεί σε διανυσματικά γραφικά Pdf, τότε είναι πιθανές προβλήματα απόδοσης στο εργαλείο προβολής Pdf.

## Δείτε επίσης

* Κλάση [PdfOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)