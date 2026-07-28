---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides dla C++ API Referencja
description: Tworzy indeks dolny i indeks górny po lewej stronie
type: docs
weight: 105
url: /pl/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metoda


Tworzy indeks dolny i indeks górny po lewej stronie

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Indeks dolny (niższy indeks po lewej stronie) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Indeks górny (wyższy indeks po lewej stronie) |

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

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) metoda


Tworzy indeks dolny i indeks górny po lewej stronie

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Indeks dolny (niższy indeks po lewej stronie) |
| superscript | [System::String](../../../system/string/) | Indeks górny (wyższy indeks po lewej stronie) |

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
* Klasa [IMathElement](../../imathelement/)
* Klasa [MathElementBase](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)