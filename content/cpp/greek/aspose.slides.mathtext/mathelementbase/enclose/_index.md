---
title: Enclose()
second_title: Aspose.Slides για C++ API Reference
description: Τοποθετεί ένα μαθηματικό στοιχείο σε παρενθέσεις
type: docs
weight: 27
url: /el/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() method

Τοποθετεί ένα μαθηματικό στοιχείο σε παρενθέσεις

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```

### Return Value

Το μαθηματικό στοιχείο τύπου [IMathDelimiter](../../imathdelimiter/) το οποίο περιλαμβάνει τις παρενθέσεις

## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) μέθοδος

Τοποθετεί ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως περιτύλιγμα

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| beginningCharacter | char16_t | Αρχικός χαρακτήρας (συνήθως αριστερή αγκύλη) |
| endingCharacter | char16_t | Τελικός χαρακτήρας (συνήθως δεξιά αγκύλη) |

### Τιμή Επιστροφής

Το μαθηματικό στοιχείο τύπου [IMathDelimiter](../../imathdelimiter/) το οποίο περιλαμβάνει τους καθορισμένους χαρακτήρες ως περιτύλιγμα

## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathDelimiter](../../imathdelimiter/)
* Κλάση [MathElementBase](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)