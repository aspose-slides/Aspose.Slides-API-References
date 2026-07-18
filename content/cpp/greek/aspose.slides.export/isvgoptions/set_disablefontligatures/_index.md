---
title: set_DisableFontLigatures()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση λιγκατών. Όταν οριστεί σε true, οι λιγκατόντες θα απενεργοποιηθούν στην παραγόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα είναι false.
type: docs
weight: 339
url: /el/aspose.slides.export/isvgoptions/set_disablefontligatures/
---
## ISVGOptions::set_DisableFontLigatures(bool) μέθοδος

Ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση λιγκατών. Όταν οριστεί σε **true**, οι λιγκατόντες θα απενεργοποιηθούν στην παραγόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα είναι **false**.

```cpp
virtual void Aspose::Slides::Export::ISVGOptions::set_DisableFontLigatures(bool value)=0
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Απενεργοποίηση των λιγκατών στην απόδοση κειμένου

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Δείτε επίσης

* Κλάση [ISVGOptions](../)
* Περιοχή ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)