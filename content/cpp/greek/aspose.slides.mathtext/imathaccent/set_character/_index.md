---
title: set_Character()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Χαρακτήρας τόνου Η τιμή πρέπει να βρίσκεται εντός του εύρους (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαστικός Καμπύλος Διαβήτης (U+0302)"
type: docs
weight: 27
url: /el/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) μέθοδος


Χαρακτήρας τόνου Η τιμή πρέπει να βρίσκεται εντός του εύρους (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαστικό Διαβήτης Καμπύλης (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Δείτε επίσης

* Κλάση [IMathAccent](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)