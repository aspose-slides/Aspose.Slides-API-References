---
title: get_AlignScripts()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει την ευθυγράμμιση του υπο- και υπερ-εκθέτη. Όταν είναι true, ο υποεκθέτης και ο υπερεκθέτης ευθυγραμμίζονται οριζόντια μεταξύ τους. Όταν είναι false, προσαρμόζονται στο σχήμα της βάσης. Η προεπιλεγμένη τιμή είναι false.
type: docs
weight: 40
url: /el/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() μέθοδος

Καθορίζει την ευθυγράμμιση του υπο- και υπερ-εκθέτη. Όταν η τιμή είναι true, ο υποεκθέτης και ο υπερεκθέτης ευθυγραμμίζονται οριζόντια μεταξύ τους. Όταν η τιμή είναι false, προσαρμόζονται στο σχήμα της βάσης. Η προεπιλεγμένη τιμή είναι false.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## Δείτε επίσης

* Κλάση [IMathRightSubSuperscriptElement](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)