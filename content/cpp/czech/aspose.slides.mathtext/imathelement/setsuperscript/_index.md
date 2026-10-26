---
title: SetSuperscript()
second_title: Aspose.Slides pro C++ – reference API
description: Vytvoří horní index
type: docs
weight: 92
url: /cs/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) method


Vytvoří horní index

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Horní index (pravý horní index) |

### Návratová hodnota

Nový matematický prvek typu [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Poznámky



Příklad: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) method


Vytvoří horní index

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Horní index (pravý horní index) |

### Návratová hodnota

Nový matematický prvek typu [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Poznámky



Příklad: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Třída [IMathElement](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)