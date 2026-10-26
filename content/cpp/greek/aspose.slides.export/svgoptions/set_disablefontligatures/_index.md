---
title: set_DisableFontLigatures()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση λιγιατούρων. Όταν οριστεί σε true, οι λιγιατούρες θα απενεργοποιηθούν στο παραγόμενο αποτέλεσμα. Από προεπιλογή, αυτή η ιδιότητα ορίζεται σε false.
type: docs
weight: 339
url: /el/aspose.slides.export/svgoptions/set_disablefontligatures/
---
## SVGOptions::set_DisableFontLigatures(bool) μέθοδος


Ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς χρήση λιγιατούρων. Όταν οριστεί σε **true**, οι λιγιατούρες θα απενεργοποιηθούν στο παραγόμενο αποτέλεσμα. Από προεπιλογή, αυτή η ιδιότητα ορίζεται σε **false**.

```cpp
void Aspose::Slides::Export::SVGOptions::set_DisableFontLigatures(bool value) override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Απενεργοποίηση των λιγιατούρων στην απόδοση κειμένου

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Δείτε επίσης

* Κλάση [SVGOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)