---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza az alsó és felső indexet a bal oldalon
type: docs
weight: 118
url: /hu/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metódus

Létrehozza az alsó és felső indexet a bal oldalon

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Alsó index (alsó index a bal oldalon) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Felső index (felső index a bal oldalon) |

### Visszatérési érték

Új [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/) típusú matematikai elem
## Megjegyzések

Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) metódus

Létrehozza az alsó és felső indexet a bal oldalon

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```

### Paraméterek

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Alsó index (alsó index a bal oldalon) |
| superscript | [System::String](../../../system/string/) | Felső index (felső index a bal oldalon) |

### Visszatérési érték

Új [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/) típusú matematikai elem
## Megjegyzések

Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Osztály [IMathElement](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)