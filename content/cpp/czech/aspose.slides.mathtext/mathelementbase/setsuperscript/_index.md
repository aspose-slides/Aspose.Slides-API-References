---
title: SetSuperscript()
second_title: Aspose.Slides pro C++ API Reference
description: Vytváří horní index
type: docs
weight: 79
url: /cs/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) metoda


Vytváří horní index

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Superscript (horní index vpravo) |

### Návratová hodnota

Nový matematický prvek typu [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Poznámky



Příklad: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) metoda


Vytváří horní index

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Superscript (horní index vpravo) |

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
* Třída [IMathElement](../../imathelement/)
* Třída [MathElementBase](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)