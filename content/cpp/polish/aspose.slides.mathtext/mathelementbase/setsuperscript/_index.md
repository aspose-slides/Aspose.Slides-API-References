---
title: SetSuperscript()
second_title: Aspose.Slides dla C++ – referencja API
description: Tworzy indeks górny
type: docs
weight: 79
url: /pl/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) method

Tworzy indeks górny

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Indeks górny (górny indeks po prawej) |

### Wartość zwracana

New math element of type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Uwagi



Przykład:
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) method

Tworzy indeks górny

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Indeks górny (górny indeks po prawej) |

### Wartość zwracana

New math element of type [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Uwagi



Przykład:
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathElementBase](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)