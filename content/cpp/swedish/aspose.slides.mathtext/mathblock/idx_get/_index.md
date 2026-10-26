---
title: idx_get()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar IMathElement på det angivna indexet.
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) metod


Hämtar [IMathElement](../../imathelement/) på det angivna indexet.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet för elementet |

### Returvärde

Det matematiska elementet.

## Anmärkningar



Exempel: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathBlock](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)