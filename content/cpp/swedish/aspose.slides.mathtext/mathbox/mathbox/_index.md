---
title: MathBox()
second_title: Aspose.Slides för C++ API-referens
description: Initierar MathBox med det specificerade elementet som argument
type: docs
weight: 144
url: /sv/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) konstruktör


Initierar [MathBox](../) med det specificerade elementet som argument

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Basiselementet som boxen tillämpas på. Kan vara null. |
## Anmärkningar



Exempel: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathBox](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)