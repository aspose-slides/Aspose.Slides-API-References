---
title: SetSuperscript()
second_title: Aspose.Slides for C++ API referencia
description: Szuperindexet hoz létre
type: docs
weight: 92
url: /hu/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) metódus


Szuperindexet hoz létre

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Felső index (jobb oldali felső index) |

### Visszatérési érték

Új matematikai elem típusa [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Megjegyzések



Példa: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) metódus


Szuperindexet hoz létre

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Felső index (jobb oldali felső index) |

### Visszatérési érték

Új matematikai elem típusa [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Megjegyzések



Példa: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Osztály [IMathElement](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)