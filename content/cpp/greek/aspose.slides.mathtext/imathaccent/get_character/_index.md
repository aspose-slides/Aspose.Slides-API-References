---
title: get_Character()
second_title: Αναφορά API Aspose.Slides για C++
description: "Χαρακτήρας τονισμού Η τιμή πρέπει να είναι εντός του εύρους (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαστική περισπωμένη (U+0302)"
type: docs
weight: 14
url: /el/aspose.slides.mathtext/imathaccent/get_character/
---
## IMathAccent::get_Character() μέθοδος

Χαρακτήρας τονισμού Η τιμή πρέπει να είναι μέσα στο εύρος των (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) Προεπιλεγμένη τιμή: Συνδυαστική περισπωμένη (U+0302)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathAccent::get_Character()=0
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