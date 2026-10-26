---
title: Add()
second_title: Αναφορά API Aspose.Slides για C++
description: Προσθέτει IMathBlock στο τέλος της συλλογής.
type: docs
weight: 14
url: /el/aspose.slides.mathtext/imathblockcollection/add/
---
## IMathBlockCollection::Add(System::SharedPtr\<IMathBlock\>) μέθοδος


Προσθέτει [IMathBlock](../../imathblock/) στο τέλος της συλλογής.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Add(System::SharedPtr<IMathBlock> item)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Ένα μαθηματικό μπλοκ που θα προστεθεί στο τέλος της συλλογής |
## Σχόλια



Παράδειγμα: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathBlock](../../imathblock/)
* Κλάση [IMathBlockCollection](../)
* Χώρος ονόματος [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)