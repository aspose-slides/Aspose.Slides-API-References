---
title: MathRadical()
second_title: Aspose.Slides för C++ API-referens
description: Initierar en ny instans av MathRadical-klassen.
type: docs
weight: 53
url: /sv/aspose.slides.mathtext/mathradical/mathradical/
---
## MathRadical::MathRadical(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor


Initierar en ny instans av klassen [MathRadical](../).

```cpp
Aspose::Slides::MathText::MathRadical::MathRadical(System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> degreeArgument)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Bas |
| degreeArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Grad |
## Anmärkningar



Exempel: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathRadical](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)