---
title: Group()
second_title: Aspose.Slides για C++ API Αναφορά
description: Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας μια κάτω αγκύλη
type: docs
weight: 248
url: /el/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() μέθοδος

Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας μια κάτω αγκύλη

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```

### Τιμή επιστροφής

Νέα παρουσία τύπου [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) μέθοδος

Τοποθετεί αυτό το στοιχείο σε μια ομάδα χρησιμοποιώντας έναν χαρακτήρα ομαδοποίησης όπως η κάτω αγκύλη ή κάποιον άλλο

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| character | char16_t | Χαρακτήρας ομαδοποίησης όπως BOTTOM CURLY BRACKET (U+23DF) ή οποιοδήποτε άλλο |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Θέση του χαρακτήρα ομαδοποίησης |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |

### Τιμή επιστροφής

Νέα παρουσία τύπου [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## Δείτε επίσης

* Απαρίθμηση [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Κλάση [IMathElement](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)