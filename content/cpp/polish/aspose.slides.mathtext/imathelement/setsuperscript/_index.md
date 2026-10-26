---
title: SetSuperscript()
second_title: Aspose.Slides dla C++ Referencja API
description: Tworzy indeks górny
type: docs
weight: 92
url: /pl/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) metoda

Tworzy indeks górny

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Indeks górny (górny indeks po prawej) |

### Wartość zwracana

Nowy element matematyczny typu [IMathSuperscriptElement](../../imathsuperscriptelement/)

## Uwagi



Przykład: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) metoda


Tworzy indeks górny

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Indeks górny (górny indeks po prawej) |

### Wartość zwracana

Nowy element matematyczny typu [IMathSuperscriptElement](../../imathsuperscriptelement/)

## Uwagi



Przykład: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Klasa [IMathElement](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)