---
title: Enclose()
second_title: Αναφορά API της Aspose.Slides για C++
description: Περιβάλλει τα παιδικά στοιχεία αυτού του μπλοκ σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο
type: docs
weight: 222
url: /el/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) μέθοδος

Περιβάλλει τα παιδικά στοιχεία αυτού του μπλοκ σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginning character (usually left bracket) |
| endingCharacter | char16_t | Ending character (usually right bracket) |

### Τιμή Επιστροφής

The math element of type [IMathDelimiter](../../imathdelimiter/) which includes specified characters as framing

## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) μέθοδος

Περιβάλλει τα παιδικά στοιχεία αυτού του μπλοκ σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους ως πλαίσιο και διαχωρίζει με έναν χαρακτήρα διαχωριστή

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginning character (usually left bracket) |
| endingCharacter | char16_t | Ending character (usually right bracket) |
| separatorCharacter | char16_t | Separator character |

### Τιμή Επιστροφής

The math element of type [IMathDelimiter](../../imathdelimiter/) which includes specified characters as framing and delimiter

## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Δείτε επίσης

* typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathDelimiter](../../imathdelimiter/)
* Κλάση [MathBlock](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)