---
title: RemoveAt()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής.
type: docs
weight: 170
url: /el/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) μέθοδος


Αφαιρεί το στοιχείο στον καθορισμένο δείκτη της συλλογής.

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης του στοιχείου που πρέπει να αφαιρεθεί. |
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## Δείτε επίσης

* Κλάση [MathBlock](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)