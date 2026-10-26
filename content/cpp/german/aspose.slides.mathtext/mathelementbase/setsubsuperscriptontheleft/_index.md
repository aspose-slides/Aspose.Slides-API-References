---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt Tiefstellung und Hochstellung auf der linken Seite
type: docs
weight: 105
url: /de/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) Methode

Erstellt Tiefstellung und Hochstellung auf der linken Seite

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Tiefstellung (niedriger Index auf der linken Seite) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Hochstellung (höherer Index auf der linken Seite) |

### Rückgabewert

Neues Math-Element vom Typ [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## Bemerkungen



Beispiel:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) Methode

Erstellt Tiefstellung und Hochstellung auf der linken Seite

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Tiefstellung (niedriger Index auf der linken Seite) |
| superscript | [System::String](../../../system/string/) | Hochstellung (höherer Index auf der linken Seite) |

### Rückgabewert

Neues Math-Element vom Typ [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## Bemerkungen



Beispiel:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)