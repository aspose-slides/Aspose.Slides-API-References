---
title: set_DisableFontLigatures()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση συνδέσμων. Όταν οριστεί σε true, οι συνδέσμοι θα απενεργοποιηθούν στην παραγόμενη έξοδο. Κατά προεπιλογή, αυτή η ιδιότητα ορίζεται σε false.
type: docs
weight: 118
url: /el/aspose.slides.export/ihtml5options/set_disablefontligatures/
---
## IHtml5Options::set_DisableFontLigatures(bool) μέθοδος


Ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση συνδέσμων. Όταν οριστεί σε **true**, οι συνδέσμοι θα απενεργοποιηθούν στην παραγόμενη έξοδο. Κατά προεπιλογή, αυτή η ιδιότητα ορίζεται σε **false**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_DisableFontLigatures(bool value)=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Απενεργοποιήστε τους συνδέσμους στην απόδοση κειμένου

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Δείτε επίσης

* Κλάση [IHtml5Options](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)