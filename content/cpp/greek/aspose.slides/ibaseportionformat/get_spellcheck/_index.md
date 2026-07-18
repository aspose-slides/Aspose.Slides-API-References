---
title: get_SpellCheck()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει μια τιμή που υποδεικνύει εάν ο έλεγχος ορθογραφίας είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα ορίζεται σε false, οι ορθογραφικοί έλεγχοι για στοιχεία κειμένου καταστέλλονται. Όταν ορίζεται σε true, ο έλεγχος ορθογραφίας επιτρέπεται. Η προεπιλεγμένη τιμή είναι false.
type: docs
weight: 599
url: /el/aspose.slides/ibaseportionformat/get_spellcheck/
---
## IBasePortionFormat::get_SpellCheck() μέθοδος

Λαμβάνει μια τιμή που υποδεικνύει εάν ο έλεγχος ορθογραφίας είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα ορίζεται σε false, οι ορθογραφικοί έλεγχοι για στοιχεία κειμένου καταστέλλονται. Όταν ορίζεται σε true, ο έλεγχος ορθογραφίας επιτρέπεται. Η προεπιλεγμένη τιμή είναι **false**.

```cpp
virtual bool Aspose::Slides::IBasePortionFormat::get_SpellCheck()=0
```

## Σημειώσεις

Το επόμενο παράδειγμα δείχνει την ενεργοποίηση της σημαίας SpellCheck πριν από την αποθήκευση της παρουσίασης: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Access the first portion of text inside the first shape on the first slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Enable spell checking for this text portion
portion->get_PortionFormat()->set_SpellCheck(true);
// Save the modified presentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [IBasePortionFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)