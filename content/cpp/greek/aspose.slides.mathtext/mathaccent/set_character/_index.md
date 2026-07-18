---
title: set_Character()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Χαρακτήρας Προφοράς Η τιμή πρέπει να είναι στο εύρος (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Διαβήτης κυρτής προφοράς (U+0302)"
type: docs
weight: 27
url: /el/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) μέθοδος


Χαρακτήρας Προφοράς Η τιμή πρέπει να βρίσκεται στο εύρος (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Combining Circumflex Accent (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Δείτε επίσης

* Κλάση [MathAccent](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)