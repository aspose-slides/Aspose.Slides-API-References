---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αληθής για μετατροπή όλων των μετααρχειών που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Γράψτε bool.
type: docs
weight: 339
url: /el/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) μέθοδος


Αληθής για μετατροπή όλων των μετααρχειών που χρησιμοποιούνται σε μια παρουσίαση σε εικόνες PNG. Γράψτε **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## Παρατηρήσεις


Η προεπιλογή είναι **true**. Έγγραφο Pdf μπορεί να περιέχει διανυσματικά γραφικά και ραστερ εικόνες. Εάν το SaveMetafilesAsPng οριστεί σε true, τότε η πηγή Metafile εικόνα μετατρέπεται σε Png μορφή και αποθηκεύεται στο Pdf ως ραστερ εικόνα. Εάν το SaveMetafilesAsPng οριστεί σε false, τότε η πηγή Metafile μετατρέπεται σε Pdf διανυσματικά γραφικά. Κάθε προσέγγιση έχει πλεονεκτήματα και μειονεκτήματα. Για παράδειγμα, εάν το Metafile μετατραπεί σε PNG, τότε κάποια απώλεια ποιότητας είναι δυνατή κατά την κλιμάκωση του τελικού εγγράφου. Εάν το Metafile μετατραπεί σε Pdf διανυσματικά γραφικά, τότε είναι πιθανά προβλήματα απόδοσης στο εργαλείο προβολής Pdf.

## Δείτε επίσης

* Κλάση [PdfOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)