---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides for C++ API Referencia
description: Létrehozza a bal oldali alsó és felső indexet
type: docs
weight: 105
url: /hu/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metódus

Létrehozza az alsó és felső indexet a bal oldalon

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Alsó index a bal oldalon |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Felső index a bal oldalon |

### Visszatérési érték

Új matematikai elem a(z) [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/) típusból

## Megjegyzések



Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) metódus

Létrehozza az alsó és felső indexet a bal oldalon

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Alsó index a bal oldalon |
| superscript | [System::String](../../../system/string/) | Felső index a bal oldalon |

### Visszatérési érték

Új matematikai elem a(z) [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/) típusból

## Megjegyzések



Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathElementBase](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)