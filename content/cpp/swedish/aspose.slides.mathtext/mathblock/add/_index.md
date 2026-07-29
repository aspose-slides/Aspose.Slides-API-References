---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till ett matematiskt element i slutet av samlingen.
type: docs
weight: 79
url: /sv/aspose.slides.mathtext/mathblock/add/
---
## MathBlock::Add(System::SharedPtr\<IMathElement\>) metod

Lägger till ett matematiskt element i slutet av samlingen.

```cpp
void Aspose::Slides::MathText::MathBlock::Add(System::SharedPtr<IMathElement> item) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Den [IMathElement](../../imathelement/) som ska läggas till i slutet av samlingen. |
## Anmärkningar

Exempel:
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
mathBlock->Add(System::MakeObject<MathematicalText>(u"+"));
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)