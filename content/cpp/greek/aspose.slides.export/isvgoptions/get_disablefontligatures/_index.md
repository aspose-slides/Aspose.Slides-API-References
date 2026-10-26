---
title: get_DisableFontLigatures()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνενώσεων. Όταν οριστεί σε true, οι συνενώσεις θα απενεργοποιηθούν στην παραγόμενη έξοδο. Εξ ορισμού, αυτή η ιδιότητα ορίζεται σε false.
type: docs
weight: 326
url: /el/aspose.slides.export/isvgoptions/get_disablefontligatures/
---
## ISVGOptions::get_DisableFontLigatures() μέθοδος


Επιστρέφει τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση συνενώσεων. Όταν οριστεί σε **true**, οι συνενώσεις θα απενεργοποιηθούν στην παραγόμενη έξοδο. Εξ ορισμού, αυτή η ιδιότητα ορίζεται σε **false**.

```cpp
virtual bool Aspose::Slides::Export::ISVGOptions::get_DisableFontLigatures()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Απενεργοποίηση των συνενώσεων στην απόδοση κειμένου

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Δείτε επίσης

* Κλάση [ISVGOptions](../)
* Ονομαχώρος [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)