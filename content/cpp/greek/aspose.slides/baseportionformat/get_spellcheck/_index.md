---
title: get_SpellCheck()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει μια τιμή που υποδεικνύει αν ο έλεγχος ορθογραφίας είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα οριστεί σε false, οι έλεγχοι ορθογραφίας για στοιχεία κειμένου καταστέλλονται. Όταν οριστεί σε true, επιτρέπεται ο έλεγχος ορθογραφίας. Η προεπιλεγμένη τιμή είναι false.
type: docs
weight: 599
url: /el/aspose.slides/baseportionformat/get_spellcheck/
---
## BasePortionFormat::get_SpellCheck() μέθοδος


Επιστρέφει μια τιμή που υποδεικνύει εάν ο έλεγχος ορθογραφίας είναι ενεργοποιημένος για το τμήμα κειμένου. Όταν αυτή η ιδιότητα οριστεί σε false, οι έλεγχοι ορθογραφίας για στοιχεία κειμένου καταστέλλονται. Όταν οριστεί σε true, επιτρέπεται ο έλεγχος ορθογραφίας. Η προεπιλεγμένη τιμή είναι **false**.

```cpp
bool Aspose::Slides::BasePortionFormat::get_SpellCheck() override
```

## Σχόλια


Το επόμενο παράδειγμα δείχνει την ενεργοποίηση της σημαίας SpellCheck πριν από την αποθήκευση της παρουσίασης: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Πρόσβαση στο πρώτο τμήμα κειμένου μέσα στο πρώτο σχήμα στην πρώτη διαφάνεια
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Ενεργοποίηση ελέγχου ορθογραφίας για αυτό το τμήμα κειμένου
portion->get_PortionFormat()->set_SpellCheck(true);
// Αποθήκευση της τροποποιημένης παρουσίασης
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [BasePortionFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)