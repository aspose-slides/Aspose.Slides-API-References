---
title: set_AlignScripts()
second_title: Aspose.Slides για C++ API Αναφορά
description: Καθορίζει την ευθυγράμμιση του δείκτη/υπερδείκτη. Όταν είναι true, ο δείκτης και ο υπερδείκτης ευθυγραμμίζονται οριζόντια μεταξύ τους. Όταν είναι false, προσαρμόζονται στο σχήμα της βάσης. Η προεπιλεγμένη τιμή είναι false.
type: docs
weight: 40
url: /el/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) μέθοδος

Καθορίζει την ευθυγράμμιση του δείκτη/υπερδείκτη. Όταν είναι true, ο δείκτης και ο υπερδείκτης ευθυγραμμίζονται οριζόντια μεταξύ τους. Όταν είναι false, προσαρμόζονται στο σχήμα της βάσης. Η προεπιλεγμένη τιμή είναι false.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
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

* Κλάση [MathRightSubSuperscriptElement](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)