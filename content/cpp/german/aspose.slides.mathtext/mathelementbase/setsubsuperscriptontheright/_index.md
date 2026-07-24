---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt Tief- und Hochstellung rechts
type: docs
weight: 92
url: /de/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) Methode

Erstellt Tief- und Hochstellung rechts

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Tiefstellung (unterer Index rechts) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Hochstellung (oberer Index rechts) |

### Rückgabewert

Neues Math-Element vom Typ [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Anmerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) Methode


Erstellt Tief- und Hochstellung rechts

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Tiefstellung (unterer Index rechts) |
| superscript | [System::String](../../../system/string/) | Hochstellung (oberer Index rechts) |

### Rückgabewert

Neues Math-Element vom Typ [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Anmerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)