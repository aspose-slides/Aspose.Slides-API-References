---
title: set_AlignScripts()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καθορίζει τη στοίχηση του κατώτερου/ανώτερου δείκτη. Όταν είναι true, ο κατώτερος δείκτης και ο ανώτερος δείκτης ευθυγραμμίζονται οριζόντια μεταξύ τους. Όταν είναι false, προσαρμόζονται ώστε να ταιριάζουν με το σχήμα της βάσης. Η προεπιλεγμένη τιμή είναι false.
type: docs
weight: 53
url: /el/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) μέθοδος


Καθορίζει τη στοίχηση του κατώτερου δείκτη/ανώτερου δείκτη. Όταν είναι true, ο κατώτερος δείκτης και ο ανώτερος δείκτης ευθυγραμμίζονται οριζόντια μεταξύ τους. Όταν είναι false, συμπιέζονται ώστε να ταιριάζουν με το σχήμα της βάσης. Η προεπιλεγμένη τιμή είναι false.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
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