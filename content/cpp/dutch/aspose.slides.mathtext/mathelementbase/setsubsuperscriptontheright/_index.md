---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt subscript en superscript aan de rechterkant
type: docs
weight: 92
url: /nl/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) methode


Maakt subscript en superscript aan de rechterkant

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Subscript (lagere index aan de rechterkant) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Superscript (hogere index aan de rechterkant) |

### Retourwaarde

Nieuw wiskundig element van type [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Opmerkingen



Voorbeeld:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) methode


Maakt subscript en superscript aan de rechterkant

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscript (lagere index aan de rechterkant) |
| superscript | [System::String](../../../system/string/) | Superscript (hogere index aan de rechterkant) |

### Retourwaarde

Nieuw wiskundig element van type [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Opmerkingen



Voorbeeld:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)