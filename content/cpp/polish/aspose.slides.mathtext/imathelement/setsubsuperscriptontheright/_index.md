---
title: SetSubSuperscriptOnTheRight()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Tworzy indeks dolny i górny po prawej
type: docs
weight: 105
url: /pl/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Tworzy indeks dolny i górny po prawej

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Indeks dolny (niższy indeks po prawej) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Indeks górny (wyższy indeks po prawej) |

### Wartość zwracana

Nowy element matematyczny typu [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Uwagi



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) method


Tworzy indeks dolny i górny po prawej

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Indeks dolny (niższy indeks po prawej) |
| superscript | [System::String](../../../system/string/) | Indeks górny (wyższy indeks po prawej) |

### Wartość zwracana

Nowy element matematyczny typu [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Uwagi



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)