---
title: get_DisableFontLigatures()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνόδων. Όταν οριστεί σε true, οι συνόδοι θα απενεργοποιηθούν στην παραγόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα είναι ορισμένη σε false.
type: docs
weight: 105
url: /el/aspose.slides.export/ihtml5options/get_disablefontligatures/
---
## IHtml5Options::get_DisableFontLigatures() μέθοδος

Λαμβάνει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνόδων. Όταν οριστεί σε **true**, οι συνόδοι θα απενεργοποιηθούν στην παραγόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα είναι ορισμένη σε **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_DisableFontLigatures()=0
```

## Σχόλια

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Απενεργοποίηση συνόδων στην απόδοση κειμένου

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Δείτε επίσης

* Κλάση [IHtml5Options](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)