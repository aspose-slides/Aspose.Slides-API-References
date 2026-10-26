---
title: RemoveAt()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort ett objekt vid det angivna indexet i samlingen.
type: docs
weight: 53
url: /sv/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) metod


Tar bort ett objekt vid det angivna indexet i samlingen.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet för objektet som ska tas bort. |
## Anmärkningar



Exempel: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## Se även

* Klass [IMathBlockCollection](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)