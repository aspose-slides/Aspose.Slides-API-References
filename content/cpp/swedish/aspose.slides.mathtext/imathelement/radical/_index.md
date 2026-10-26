---
title: Radical()
second_title: Aspose.Slides för C++ API-referens
description: Anger den matematiska roten av den angivna graden från det specificerade argumentet.
type: docs
weight: 131
url: /sv/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) method


Anger den matematiska roten av den angivna graden från det specificerade argumentet.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argument för Radical |

### Returvärde

Ny instans av typ [IMathRadical](../../imathradical/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) method


Anger den matematiska roten av den angivna graden från det specificerade argumentet.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argument för Radical |

### Returvärde

Ny instans av typ [IMathRadical](../../imathradical/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathRadical](../../imathradical/)
* Klass [IMathElement](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)