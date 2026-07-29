---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides för C++ API-referens
description: Skapar nedsänkt och upphöjd text till höger
type: docs
weight: 105
url: /sv/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metod

Skapar nedsänkt och upphöjd text till höger

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Nedsänkt (lägre index på höger) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Upphöjd (högre index på höger) |

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

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) metod

Skapar nedsänkt och upphöjd text till höger

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Nedsänkt (lägre index på höger) |
| superscript | [System::String](../../../system/string/) | Upphöjd (högre index på höger) |

### Returvärde

Nytt matematiskt element av typen [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Anmärkningar

Exempel:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Klass [IMathElement](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)