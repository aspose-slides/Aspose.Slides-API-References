---
title: idx_get()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar elementet på det angivna indexet. Skrivskyddad IMathElement.
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/imathelementcollection/idx_get/
---
## IMathElementCollection::idx_get(int32_t) metod


Hämtar elementet på det angivna indexet. Skrivskyddad [IMathElement](../../imathelement/).

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathElementCollection::idx_get(int32_t index)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet för objektet att hämta |
## Anmärkningar



Exempel: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = collection->idx_get(0);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [IMathElementCollection](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)