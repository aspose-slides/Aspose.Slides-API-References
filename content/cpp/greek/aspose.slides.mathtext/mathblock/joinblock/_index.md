---
title: JoinBlock()
second_title: Αναφορά API Aspose.Slides για C++
description: Συνδέει ένα άλλο μαθηματικό μπλοκ με αυτό
type: docs
weight: 196
url: /el/aspose.slides.mathtext/mathblock/joinblock/
---
## MathBlock::JoinBlock(System::SharedPtr\<IMathBlock\>) μέθοδος


Συνδέει ένα άλλο μαθηματικό μπλοκ με αυτό

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::JoinBlock(System::SharedPtr<IMathBlock> other) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| other | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Το μπλοκ που συνδέεται |

### Τιμή Επιστροφής

Αυτό το μαθηματικό μπλοκ μετά τη σύνδεση
## Σχόλια



Παράδειγμα: 
```cpp
auto block1 = System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"c"), System::MakeObject<MathematicalText>(u"2"))->Join(System::MakeObject<MathematicalText>(u"="));
auto block2 = System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"a"), System::MakeObject<MathematicalText>(u"2"))->Join(System::MakeObject<MathematicalText>(u"+"))->Join(System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"b"), System::MakeObject<MathematicalText>(u"2")));
auto block3 = block1->JoinBlock(block2);
```

## Δείτε επίσης

* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathBlock](../../imathblock/)
* Κλάση [MathBlock](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)