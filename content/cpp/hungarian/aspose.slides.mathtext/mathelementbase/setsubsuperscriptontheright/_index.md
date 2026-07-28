---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza az alul- és felső indexet a jobb oldalon
type: docs
weight: 92
url: /hu/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metódus


Létrehozza az alul- és felső indexet a jobb oldalon

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Alulindex (alsó index a jobb oldalon) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Felsőindex (felső index a jobb oldalon) |

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

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) metódus


Létrehozza az alul- és felső indexet a jobb oldalon

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Alulindex (alsó index a jobb oldalon) |
| superscript | [System::String](../../../system/string/) | Felsőindex (felső index a jobb oldalon) |

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
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathElementBase](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)