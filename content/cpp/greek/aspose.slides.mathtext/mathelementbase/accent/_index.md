---
title: Accent()
second_title: Αναφορά API Aspose.Slides για C++
description: Ορίζει ένα σημάδι τονισμού (έναν χαρακτήρα στην κορυφή του στοιχείου)
type: docs
weight: 196
url: /el/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) μέθοδος

Ορίζει ένα σημάδι τονισμού (έναν χαρακτήρα στην κορυφή του στοιχείου)

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char16_t | Χαρακτήρας τονισμού. Η τιμή πρέπει να βρίσκεται εντός του εύρους (U+0300\\u2013U+036F) ή (U+20D0\\u2013U+20EF) |

### Return Value

Νέα παρουσία τύπου [IMathAccent](../../imathaccent/)

## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Τάξη [IMathAccent](../../imathaccent/)
* Τάξη [MathElementBase](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)