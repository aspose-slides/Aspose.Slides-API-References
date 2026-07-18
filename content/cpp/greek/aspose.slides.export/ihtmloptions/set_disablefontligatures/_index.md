---
title: set_DisableFontLigatures()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση συνόλων χαρακτήρων. Όταν οριστεί σε true, τα σύνολα χαρακτήρων θα απενεργοποιηθούν στην αποδοθείσα έξοδο. Από προεπιλογή, αυτή η ιδιότητα έχει οριστεί σε false.
type: docs
weight: 196
url: /el/aspose.slides.export/ihtmloptions/set_disablefontligatures/
---
## IHtmlOptions::set_DisableFontLigatures(bool) μέθοδος

Ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση συνόλων χαρακτήρων. Όταν οριστεί σε **true**, τα σύνολα χαρακτήρων θα απενεργοποιηθούν στην αποδοθείσα έξοδο. Από προεπιλογή, αυτή η ιδιότητα έχει οριστεί σε **false**.

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_DisableFontLigatures(bool value)=0
```

## Σχόλια

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Απενεργοποίηση συνόλων χαρακτήρων στην απόδοση κειμένου

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Δείτε επίσης

* Κλάση [IHtmlOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)