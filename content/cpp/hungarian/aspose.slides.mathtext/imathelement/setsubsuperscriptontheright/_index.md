---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehozza az alsó és felső indexet a jobb oldalon
type: docs
weight: 105
url: /hu/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metódus

Létrehozza az alsó indexet és a felső indexet a jobb oldalon

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Alsó index (az alsó index a jobb oldalon) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Felső index (a felső index a jobb oldalon) |

### Visszatérési érték

Új matematikai elem a(z) [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/) típusú

## Megjegyzések

Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) metódus

Létrehozza az alsó indexet és a felső indexet a jobb oldalon

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Alsó index (az alsó index a jobb oldalon) |
| superscript | [System::String](../../../system/string/) | Felső index (a felső index a jobb oldalon) |

### Visszatérési érték

Új matematikai elem a(z) [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/) típusú

## Megjegyzések

Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Osztály [IMathElement](../)
* Osztály [String](../../../system/string/)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)