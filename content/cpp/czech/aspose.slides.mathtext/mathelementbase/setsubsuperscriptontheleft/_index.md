---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides pro C++ API reference
description: Vytvoří dolní a horní index vlevo
type: docs
weight: 105
url: /cs/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda


Vytvoří dolní a horní index vlevo

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Podskript (dolní index vlevo) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Superskript (horní index vlevo) |

### Návratová hodnota

Nový matematický prvek typu [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) metoda


Vytvoří dolní a horní index vlevo

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Podskript (dolní index vlevo) |
| superscript | [System::String](../../../system/string/) | Superskript (horní index vlevo) |

### Návratová hodnota

Nový matematický prvek typu [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathElementBase](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)