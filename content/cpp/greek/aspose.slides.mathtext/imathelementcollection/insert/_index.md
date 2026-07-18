---
title: Insert()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εισάγει ένα μαθηματικό στοιχείο στη συλλογή στη συγκεκριμένη θέση.
type: docs
weight: 53
url: /el/aspose.slides.mathtext/imathelementcollection/insert/
---
## IMathElementCollection::Insert(int32_t, System::SharedPtr\<IMathElement\>) μέθοδος

Εισάγει ένα μαθηματικό στοιχείο στη συλλογή στη συγκεκριμένη θέση.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::Insert(int32_t index, System::SharedPtr<IMathElement> item)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στον οποίο πρέπει να εισαχθεί το [IMathElement](../../imathelement/). |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Το [IMathElement](../../imathelement/) προς εισαγωγή. |
## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IMathElementCollection](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)