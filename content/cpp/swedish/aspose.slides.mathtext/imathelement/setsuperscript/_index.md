---
title: SetSuperscript()
second_title: Aspose.Slides för C++ API-referens
description: Skapar upphöjd text
type: docs
weight: 92
url: /sv/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) metod

Skapar upphöjd text

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Upphöjt (övre index till höger) |

### Returvärde

Nytt matematikelement av typen [IMathSuperscriptElement](../../imathsuperscriptelement/)

## Anmärkningar



Exempel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) metod

Skapar upphöjd text

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```

### Argument

| Parameter | Type | Beskrivning |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Upphöjt (övre index till höger) |

### Returvärde

Nytt matematikelement av typen [IMathSuperscriptElement](../../imathsuperscriptelement/)

## Anmärkningar



Exempel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Klass [IMathElement](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)