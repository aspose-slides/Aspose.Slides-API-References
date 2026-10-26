---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Tworzy indeks dolny i indeks górny po lewej stronie
type: docs
weight: 118
url: /pl/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Tworzy indeks dolny i indeks górny po lewej stronie

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Indeks dolny (dolny indeks po lewej) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Indeks górny (górny indeks po lewej) |

### Wartość zwracana

Nowy element matematyczny typu [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Uwagi



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) method


Tworzy indeks dolny i indeks górny po lewej stronie

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Indeks dolny (dolny indeks po lewej) |
| superscript | [System::String](../../../system/string/) | Indeks górny (górny indeks po lewej) |

### Wartość zwracana

Nowy element matematyczny typu [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Uwagi



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Klasa [IMathElement](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)