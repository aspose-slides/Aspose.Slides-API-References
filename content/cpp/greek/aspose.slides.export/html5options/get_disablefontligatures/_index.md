---
title: get_DisableFontLigatures()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση συνόλων χαρακτήρων. Όταν οριστεί σε true, τα σύνολα χαρακτήρων θα απενεργοποιηθούν στην παραγόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα ορίζεται σε false.
type: docs
weight: 105
url: /el/aspose.slides.export/html5options/get_disablefontligatures/
---
## Html5Options::get_DisableFontLigatures() μέθοδος


Επιστρέφει τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση συνόλων χαρακτήρων. Όταν οριστεί σε **true**, τα σύνολα χαρακτήρων θα απενεργοποιηθούν στην παραγόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα ορίζεται σε **false**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_DisableFontLigatures() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Απενεργοποίηση συνόλων χαρακτήρων στην απόδοση κειμένου

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Δείτε επίσης

* Κλάση [Html5Options](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)