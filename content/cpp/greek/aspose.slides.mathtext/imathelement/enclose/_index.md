---
title: Enclose()
second_title: Aspose.Slides για C++ API Αναφορά
description: Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις
type: docs
weight: 40
url: /el/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() μέθοδος


Περιβάλλει ένα μαθηματικό στοιχείο σε παρενθέσεις

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```


### Τιμή Επιστροφής

Το μαθηματικό στοιχείο τύπου [IMathDelimiter](../../imathdelimiter/) που περιλαμβάνει τις παρενθέσεις
## Σχόλια



Παράδειγμα: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) μέθοδος


Περιβάλλει αυτό το στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| beginningCharacter | char16_t | Αρχικός χαρακτήρας (συνήθως αριστερή αγκύλη) |
| endingCharacter | char16_t | Τελικός χαρακτήρας (συνήθως δεξιά αγκύλη) |

### Τιμή Επιστροφής

Το μαθηματικό στοιχείο τύπου [IMathDelimiter](../../imathdelimiter/) που περιλαμβάνει τους καθορισμένους χαρακτήρες ως πλαίσιο
## Σχόλια



Παράδειγμα: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathDelimiter](../../imathdelimiter/)
* Κλάση [IMathElement](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)