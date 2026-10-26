---
title: MathBlock()
second_title: Αναφορά API του Aspose.Slides για C++
description: Αρχικοποιεί ένα νέο αντικείμενο της κλάσης MathBlock.
type: docs
weight: 66
url: /el/aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() κατασκευαστής

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [MathBlock](../).

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) κατασκευαστής

Δημιουργεί ένα νέο μαθηματικό μπλοκ και τοποθετεί το καθορισμένο στοιχείο σε αυτό

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το μαθηματικό στοιχείο που θα τοποθετηθεί στο μπλοκ |
## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) κατασκευαστής

Δημιουργεί ένα νέο μαθηματικό μπλοκ και τοποθετεί τα καθορισμένα στοιχεία σε αυτό

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Μαθηματικά στοιχεία που θα τοποθετηθούν στο μπλοκ |
## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [MathBlock](../)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IEnumerable](../../../system.collections.generic/ienumerable/)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)