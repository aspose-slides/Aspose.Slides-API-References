---
title: Enclose()
second_title: Aspose.Slides για C++ API Αναφορά
description: Τοποθετεί τα παιδικά στοιχεία αυτού του μπλοκ μέσα σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους, ως πλαίσιο και διαχωρίζει με έναν χαρακτήρα διαχωρισμού
type: docs
weight: 14
url: /el/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) μέθοδος


Τοποθετεί τα παιδικά στοιχεία αυτού του μπλοκ μέσα σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους, ως πλαίσιο και διαχωρίζει με έναν χαρακτήρα διαχωρισμού

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| beginningCharacter | char16_t | Χαρακτήρας έναρξης (συνήθως αριστερή αγκύλη) |
| endingCharacter | char16_t | Χαρακτήρας λήξης (συνήθως δεξιά αγκύλη) |
| separatorCharacter | char16_t | Χαρακτήρας διαχωρισμού |

### Τιμή Επιστροφής

Το μαθηματικό στοιχείο τύπου [IMathDelimiter](../../imathdelimiter/) το οποίο περιλαμβάνει τους καθορισμένους χαρακτήρες ως πλαίσιο και οριοθέτηση
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Δείτε επίσης

* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathDelimiter](../../imathdelimiter/)
* Κλάση [IMathBlock](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)