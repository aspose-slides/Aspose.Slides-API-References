---
title: set_DisableFontLigatures()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδέσεων χαρακτήρων. Όταν οριστεί σε true, οι συνδέσεις χαρακτήρων θα απενεργοποιηθούν στην παραγόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα είναι ορισμένη σε false.
type: docs
weight: 105
url: /el/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) μέθοδος


Ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδέσεων χαρακτήρων. Όταν οριστεί σε **true**, οι συνδέσεις χαρακτήρων θα απενεργοποιηθούν στην παραγόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα είναι ορισμένη σε **false**.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
```

## Σημειώσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Απενεργοποίηση συνδέσεων χαρακτήρων στην απόδοση κειμένου

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Δείτε επίσης

* Κλάση [HtmlOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)