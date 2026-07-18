---
title: get_Character()
second_title: Αναφορά API Aspose.Slides για C++
description: "Χαρακτήρας τόνου Η τιμή πρέπει να βρίσκεται εντός της περιοχής (U+0300\u2013U+036F) ή(U+20D0\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαστικό κυρτό τόνο (U+0302)"
type: docs
weight: 14
url: /el/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() μέθοδος


Χαρακτήρας τόνου Η τιμή πρέπει να βρίσκεται εντός της περιοχής (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαστικό κυρτό τόνο (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
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