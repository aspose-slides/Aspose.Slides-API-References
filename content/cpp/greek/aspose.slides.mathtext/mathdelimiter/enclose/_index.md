---
title: Enclose()
second_title: Aspose.Slides για C++ Αναφορά API
description: Καλύπτει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο
type: docs
weight: 170
url: /el/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) μέθοδος

Καλύπτει ένα μαθηματικό στοιχείο σε καθορισμένους χαρακτήρες όπως παρενθέσεις ή άλλους χαρακτήρες ως πλαίσιο

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| beginningCharacter | char16_t | Αρχικός χαρακτήρας (συνήθως αριστερή αγκύλη) |
| endingCharacter | char16_t | Τελικός χαρακτήρας (συνήθως δεξιά αγκύλη) |

### Τιμή Επιστροφής

Εάν *beginningCharacter* και *endingCharacter* είναι null, αντιστοιχες ιδιότητες λαμβάνουν μόνο τιμές και δεν δημιουργείται νέο αντικείμενο (επιστρέφει αυτό το στιγμιότυπο). Διαφορετικά, επιστρέφει νέο μαθηματικό στοιχείο τύπου Delimiter που περιλαμβάνει τους καθορισμένους χαρακτήρες ως πλαίσιο και αυτό το στιγμιότυπο του [MathDelimiter](../) περιτυλιγμένο μέσα.

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathDelimiter](../../imathdelimiter/)
* Κλάση [MathDelimiter](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)