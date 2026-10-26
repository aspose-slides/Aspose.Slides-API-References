---
title: Radical()
second_title: Aspose.Slides för C++ API-referens
description: Specificerar den matematiska roten av den angivna graden från det specificerade argumentet.
type: docs
weight: 118
url: /sv/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) method


Specificerar den matematiska roten av den angivna graden från det specificerade argumentet.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument för Radical |

### Return Value

Ny instans av typen [IMathRadical](../../imathradical/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) method


Specificerar den matematiska roten av den angivna graden från det specificerade argumentet.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argument för Radical |

### Return Value

Ny instans av typen [IMathRadical](../../imathradical/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathRadical](../../imathradical/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathElementBase](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)