---
title: SetSuperscript()
second_title: Aspose.Slides C++ API-referencia
description: Létrehozza a felső indexet
type: docs
weight: 79
url: /hu/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) metódus


Létrehozza a felső indexet

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Felső index (jobb oldali felső index) |

### Visszatérési érték

Új matematika elem típusa [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Megjegyzések



Példa: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) metódus


Létrehozza a felső indexet

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Felső index (jobb oldali felső index) |

### Visszatérési érték

Új matematika elem típusa [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Megjegyzések



Példa: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathElementBase](../)
* Osztály [String](../../../system/string/)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)