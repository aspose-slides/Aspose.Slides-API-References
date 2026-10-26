---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytváří dolní a horní index vpravo
type: docs
weight: 105
url: /cs/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda

Creates subscript and superscript on the right

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Dolní index (nižší index vpravo) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Horní index (vyšší index vpravo) |

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

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) metoda

Creates subscript and superscript on the right

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Dolní index (nižší index vpravo) |
| superscript | [System::String](../../../system/string/) | Horní index (vyšší index vpravo) |

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
* Třída [IMathElement](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)