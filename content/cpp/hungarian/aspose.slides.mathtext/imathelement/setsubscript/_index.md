---
title: SetSubscript()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza az alsó indexet
type: docs
weight: 79
url: /hu/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) metódus

Létrehozza az alsó indexet

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Alsó index (kisebb index a jobb oldalon) |

### Visszatérési érték

Új matematikai elem a(z) [IMathSubscriptElement](../../imathsubscriptelement/) típusú

## Megjegyzések



Példa: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) metódus

Létrehozza az alsó indexet

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Alsó index (kisebb index a jobb oldalon) |

### Visszatérési érték

Új matematikai elem a(z) [IMathSubscriptElement](../../imathsubscriptelement/) típusú

## Megjegyzések



Példa: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathSubscriptElement](../../imathsubscriptelement/)
* Osztály [IMathElement](../)
* Osztály [String](../../../system/string/)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)