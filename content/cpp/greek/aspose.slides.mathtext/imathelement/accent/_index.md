---
title: Accent()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ορίζει ένα σημείο τονισμού (έναν χαρακτήρα στην κορυφή αυτού του στοιχείου)
type: docs
weight: 209
url: /el/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) μέθοδος

Ορίζει ένα σημείο τονισμού (έναν χαρακτήρα στην κορυφή αυτού του στοιχείου)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char16_t | Χαρακτήρας τονισμού. Η τιμή πρέπει να βρίσκεται εντός του εύρους (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) |

### Τιμή επιστροφής

Νέα παρουσία τύπου [IMathAccent](../../imathaccent/)
## Παρατηρήσεις

Example: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathAccent](../../imathaccent/)
* Κλάση [IMathElement](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)