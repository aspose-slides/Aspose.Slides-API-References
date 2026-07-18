---
title: get_DisableFontLigatures()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδέσεων γραμμάτων. Όταν οριστεί σε true, οι συνδέσεις γραμμάτων θα απενεργοποιηθούν στην αποδοθείσα έξοδο. Από προεπιλογή, αυτή η ιδιότητα είναι ορισμένη σε false.
type: docs
weight: 183
url: /el/aspose.slides.export/ihtmloptions/get_disablefontligatures/
---
## IHtmlOptions::get_DisableFontLigatures() μέθοδος


Επιστρέφει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδέσεων γραμμάτων. Όταν οριστεί σε **true**, οι συνδέσεις γραμμάτων θα απενεργοποιηθούν στην αποδοθείσα έξοδο. Από προεπιλογή, αυτή η ιδιότητα είναι ορισμένη σε **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtmlOptions::get_DisableFontLigatures()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Απενεργοποίηση συνδέσεων γραμμάτων στην απόδοση κειμένου

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Δείτε επίσης

* Κλάση [IHtmlOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)