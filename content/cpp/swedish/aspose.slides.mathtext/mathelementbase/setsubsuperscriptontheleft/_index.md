---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides för C++ API-referens
description: Skapar nedsänkt och upphöjt på vänster sida
type: docs
weight: 105
url: /sv/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metod


Skapar nedsänkt och upphöjt på vänster sida

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Nedsänkt (lägre index på vänster) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Upphöjt (högre index på vänster) |

### Returvärde

Nytt matematiskt element av typen [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) metod


Skapar nedsänkt och upphöjt på vänster sida

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Nedsänkt (lägre index på vänster) |
| superscript | [System::String](../../../system/string/) | Upphöjt (högre index på vänster) |

### Returvärde

Nytt matematiskt element av typen [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathElementBase](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)