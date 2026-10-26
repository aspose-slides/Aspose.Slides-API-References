---
title: get_AlignScripts()
second_title: Αναφορά API Aspose.Slides για C++
description: Καθορίζει τη στοίχιση του subscript/superscript. Όταν είναι true, ο subscript και ο superscript στοιχίζονται οριζόντια μεταξύ τους. Όταν είναι false, προσαρμόζονται στο σχήμα της βάσης. Η προεπιλεγμένη τιμή είναι false.
type: docs
weight: 27
url: /el/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() μέθοδος


Καθορίζει τη στοίχιση του subscript/superscript. Όταν είναι true, ο subscript και ο superscript στοιβάζονται οριζόντια μεταξύ τους. Όταν είναι false, προσαρμόζονται στο σχήμα της βάσης. Η προεπιλεγμένη τιμή είναι false.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
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