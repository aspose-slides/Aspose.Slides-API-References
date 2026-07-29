---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides för C++ API-referens
description: Skapar nedsänkt och upphöjd text på högra sidan
type: docs
weight: 92
url: /sv/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metod


Skapar nedsänkt och upphöjd text på högra sidan

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Nedsänkt (lägre index på högra sidan) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Upphöjd (högre index på högra sidan) |

### Returvärde

Nytt matematiskt element av typen [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) metod


Skapar nedsänkt och upphöjd text på högra sidan

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Nedsänkt (lägre index på högra sidan) |
| superscript | [System::String](../../../system/string/) | Upphöjd (högre index på högra sidan) |

### Returvärde

Nytt matematiskt element av typen [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Anmärkningar



Exempel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Se också

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathElementBase](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)