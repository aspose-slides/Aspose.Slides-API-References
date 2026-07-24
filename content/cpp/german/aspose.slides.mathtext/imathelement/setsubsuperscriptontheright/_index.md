---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt Tief- und Hochstellung rechts
type: docs
weight: 105
url: /de/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) Methode


Erstellt Tief- und Hochstellung rechts

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Tiefgestellt (unterer Index rechts) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Hochgestellt (oberer Index rechts) |

### Rückgabewert

Neues Math-Element des Typs [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Hinweise



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) Methode


Erstellt Tief- und Hochstellung rechts

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Tiefgestellt (unterer Index rechts) |
| superscript | [System::String](../../../system/string/) | Hochgestellt (oberer Index rechts) |

### Rückgabewert

Neues Math-Element des Typs [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Hinweise



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)