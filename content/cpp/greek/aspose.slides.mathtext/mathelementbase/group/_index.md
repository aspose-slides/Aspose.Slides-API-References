---
title: Group()
second_title: Aspose.Slides για C++ Αναφορά API
description: Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας μια κάτω αγκύλη
type: docs
weight: 235
url: /el/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() μέθοδος


Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας μια κάτω αγκύλη

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```


### Τιμή Επιστροφής

Νέα παρουσία τύπου [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) μέθοδος


Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης όπως η κάτω αγκύλη ή κάποιον άλλο

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| character | char16_t | Χαρακτήρας ομαδοποίησης όπως το ΚΑΤΩ ΚΑΤΤΑΣΜΟΤΙΚΟ ΑΚΟΛΩΤ (U+23DF) ή οποιοσδήποτε άλλος |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Θέση του χαρακτήρα ομαδοποίησης |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Κατακόρυφη στοίχιση του χαρακτήρα ομαδοποίησης. Καθορίζει τη στοίχιση του αντικειμένου σε σχέση με τη γραμμή βάσης. Για παράδειγμα, όταν ο χαρακτήρας ομαδοποίησης είναι πάνω από το αντικείμενο, η VerticalJustification του Top σημαίνει ότι η κορυφή του αντικειμένου πέφτει στη γραμμή βάσης· όταν η VerticalJustification είναι ορισμένη σε Bottom, το κάτω μέρος του αντικειμένου είναι στη γραμμή βάσης |

### Τιμή Επιστροφής

Νέα παρουσία τύπου [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Δείτε επίσης

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Κλάση [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)