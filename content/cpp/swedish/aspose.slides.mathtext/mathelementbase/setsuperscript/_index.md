---
title: SetSuperscript()
second_title: Aspose.Slides för C++ API-referens
description: Skapar upphöjd
type: docs
weight: 79
url: /sv/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) method

Skapar upphöjd

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Upphöjd (övre index till höger) |

### Returvärde

Ny matematisk element av typ [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Anmärkningar



Exempel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) method

Skapar upphöjd

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Upphöjd (övre index till höger) |

### Returvärde

Ny matematisk element av typ [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Anmärkningar



Exempel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathElementBase](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)