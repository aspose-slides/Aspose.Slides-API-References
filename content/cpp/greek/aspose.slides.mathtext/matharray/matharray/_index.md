---
title: MathArray()
second_title: Αναφορά API του Aspose.Slides για C++
description: Δημιουργεί έναν μαθηματικό πίνακα και τοποθετεί το καθορισμένο στοιχείο σε αυτό
type: docs
weight: 144
url: /el/aspose.slides.mathtext/matharray/matharray/
---
## MathArray::MathArray(System::SharedPtr\<IMathElement\>) κατασκευαστής

Δημιουργεί έναν μαθηματικό πίνακα και τοποθετεί το καθορισμένο στοιχείο σε αυτό

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<IMathElement> element)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το στοιχείο που θα τοποθετηθεί στον πίνακα |
## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
```

## MathArray::MathArray(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) κατασκευαστής

Δημιουργεί έναν μαθηματικό πίνακα και τοποθετεί τα καθορισμένα στοιχεία σε αυτόν

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> elements)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| elements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Τα στοιχεία που θα τοποθετηθούν στον πίνακα |

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathArray](../)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)