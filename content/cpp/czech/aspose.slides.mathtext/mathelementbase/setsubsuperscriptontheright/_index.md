---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vytváří dolní a horní index napravo
type: docs
weight: 92
url: /cs/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda


Vytváří dolní a horní index napravo

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Dolní index (nižší index napravo) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Horní index (vyšší index napravo) |

### Návratová hodnota

Nový matematický prvek typu [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) metoda


Vytváří dolní a horní index napravo

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Dolní index (nižší index napravo) |
| superscript | [System::String](../../../system/string/) | Horní index (vyšší index napravo) |

### Návratová hodnota

Nový matematický prvek typu [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathElementBase](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)