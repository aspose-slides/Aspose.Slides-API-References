---
title: MathGroupingCharacter()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αρχικοποιεί μια νέα παρουσία της κλάσης MathGroupingCharacter με τον προεπιλεγμένο χαρακτήρα ομαδοποίησης U+23DF (BOTTOM CURLY BRACKET)
type: docs
weight: 92
url: /el/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) κατασκευαστής


Αρχικοποιεί μια νέα παρουσία της κλάσης [MathGroupingCharacter](../) με το προεπιλεγμένο χαρακτήρα ομαδοποίησης U+23DF (BOTTOM CURLY BRACKET)

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το βασικό στοιχείο στο οποίο εφαρμόζεται η γραμμή |
## Σχόλια



Παράδειγμα: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) κατασκευαστής


Αρχικοποιεί μια νέα παρουσία της κλάσης [MathGroupingCharacter](../).

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το βασικό στοιχείο στο οποίο εφαρμόζεται η γραμμή |
| character | char16_t | Χαρακτήρας ομαδοποίησης |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Θέση του χαρακτήρα ομαδοποίησης |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Κατακόρυφη στοίχιση του χαρακτήρα ομαδοποίησης |
## Σχόλια



Παράδειγμα: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## Δείτε επίσης

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)