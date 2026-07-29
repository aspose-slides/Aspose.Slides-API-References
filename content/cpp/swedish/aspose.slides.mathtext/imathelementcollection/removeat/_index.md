---
title: RemoveAt()
second_title: Aspose.Slides för C++ API-referens
description: Tar bort elementet på det angivna indexet i samlingen.
type: docs
weight: 105
url: /sv/aspose.slides.mathtext/imathelementcollection/removeat/
---
## IMathElementCollection::RemoveAt(int32_t) metod


Tar bort elementet på det angivna indexet i samlingen.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::RemoveAt(int32_t index)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet för elementet som ska tas bort. |
## Anmärkningar



Exempel: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->RemoveAt(2);
```

## Se även

* Klass [IMathElementCollection](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)