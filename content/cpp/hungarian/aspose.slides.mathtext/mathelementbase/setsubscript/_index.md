---
title: SetSubscript()
second_title: Aspose.Slides C++ API Referencia
description: Alsó indexet hoz létre
type: docs
weight: 66
url: /hu/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) metódus

Alsó indexet hoz létre

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Alsó index (jobb oldalon) |

### Visszatérési érték

Új matematikai elem a(z) [IMathSubscriptElement](../../imathsubscriptelement/) típusú

## Megjegyzések

Példa:
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) metódus

Alsó indexet hoz létre

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Alsó index (jobb oldalon) |

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
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathElementBase](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)