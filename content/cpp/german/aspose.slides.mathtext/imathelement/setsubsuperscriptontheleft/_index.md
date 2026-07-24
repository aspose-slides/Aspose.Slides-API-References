---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt Tief- und Hochstellung links
type: docs
weight: 118
url: /de/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) Methode

Erstellt Tief- und Hochstellung links

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Tiefstellung (unterer Index links) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Hochstellung (oberer Index links) |

### Rückgabewert

Neues mathematisches Element vom Typ [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Anmerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) Methode

Erstellt Tief- und Hochstellung links

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Tiefstellung (unterer Index links) |
| superscript | [System::String](../../../system/string/) | Hochstellung (oberer Index links) |

### Rückgabewert

Neues mathematisches Element vom Typ [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Anmerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)