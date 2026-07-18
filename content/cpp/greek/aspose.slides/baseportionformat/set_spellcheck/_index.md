---
title: set_SpellCheck()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ορίζει μια τιμή που υποδεικνύει εάν η ορθογραφική διόρθωση είναι ενεργοποιημένη για το τμήμα κειμένου. Όταν αυτή η ιδιότητα οριστεί σε false, οι ορθογραφικοί έλεγχοι για στοιχεία κειμένου καταστέλλονται. Όταν οριστεί σε true, η ορθογραφική διόρθωση επιτρέπεται. Η προεπιλεγμένη τιμή είναι false.
type: docs
weight: 612
url: /el/aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) μέθοδος

Ορίζει μια τιμή που υποδεικνύει εάν η ορθογραφική διόρθωση είναι ενεργή για το τμήμα κειμένου. Όταν αυτή η ιδιότητα οριστεί σε false, οι ορθογραφικοί έλεγχοι για στοιχεία κειμένου καταστέλλονται. Όταν οριστεί σε true, επιτρέπεται η ορθογραφική διόρθωση. Η προεπιλεγμένη τιμή είναι **false**.

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## Παρατηρήσεις

Το επόμενο παράδειγμα δείχνει την ενεργοποίηση της σημαίας SpellCheck πριν από την αποθήκευση της παρουσίασης: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Πρόσβαση στο πρώτο τμήμα κειμένου μέσα στο πρώτο σχήμα της πρώτης διαφάνειας
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Ενεργοποίηση ορθογραφικού ελέγχου για αυτό το τμήμα κειμένου
portion->get_PortionFormat()->set_SpellCheck(true);
// Αποθήκευση της τροποποιημένης παρουσίασης
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Κλάση [BasePortionFormat](../)
* Περιοχή ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)