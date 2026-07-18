---
title: get_DisableFontLigatures()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδέσεων. Όταν ορίζεται σε true, οι συνδέσεις θα απενεργοποιηθούν στην αποτυπωμένη έξοδο. Από προεπιλογή, αυτή η ιδιότητα έχει τιμή false.
type: docs
weight: 92
url: /el/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() μέθοδος


Λαμβάνει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνδέσεων. Όταν οριστεί σε **true**, οι συνδέσεις θα απενεργοποιηθούν στην αποθηκευμένη έξοδο. Από προεπιλογή, αυτή η ιδιότητα έχει τιμή **false**.

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
```

## Παρατηρήσεις


Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Απενεργοποίηση των συνδέσεων στην απόδοση του κειμένου

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Δείτε επίσης

* Κλάση [HtmlOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)