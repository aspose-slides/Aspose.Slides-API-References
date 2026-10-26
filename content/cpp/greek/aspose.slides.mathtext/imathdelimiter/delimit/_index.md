---
title: Delimit()
second_title: Aspose.Slides για το API Reference της C++
description: Διαχωρίζει τα ορίσματα χρησιμοποιώντας τον καθορισμένο χαρακτήρα οριοθέτη
type: docs
weight: 144
url: /el/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) μέθοδος

Διαχωρίζει τα ορίσματα χρησιμοποιώντας τον καθορισμένο χαρακτήρα οριοθέτη

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| separatorCharacter | char16_t | χαρακτήρας οριοθέτη |

### Τιμή Επιστροφής

Αυτό το αντικείμενο μετά την εφαρμογή του χαρακτήρα οριοθέτη
## Σχόλια



Παράδειγμα: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## Δείτε επίσης

* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)