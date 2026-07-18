---
title: set_DisableFontLigatures()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση συνδέσεων. Όταν οριστεί σε true, οι συνδέσεις θα απενεργοποιηθούν στην αποδιδόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα ορίζεται σε false.
type: docs
weight: 118
url: /el/aspose.slides.export/html5options/set_disablefontligatures/
---
## Html5Options::set_DisableFontLigatures(bool) μέθοδος

Ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση συνδέσεων. Όταν οριστεί σε **true**, οι συνδέσεις θα απενεργοποιηθούν στην αποδιδόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα ορίζεται σε **false**.

```cpp
void Aspose::Slides::Export::Html5Options::set_DisableFontLigatures(bool value) override
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Απενεργοποίηση συνδέσεων στην απόδοση κειμένου

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Δείτε επίσης

* Κλάση [Html5Options](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)