---
title: SetSuperscript()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt Hochstellung
type: docs
weight: 79
url: /de/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) Methode


Erstellt Hochstellung

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Hochstellung (obere Index rechts) |

### Rückgabewert

Neues Mathelement vom Typ [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Bemerkungen



Beispiel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) Methode


Erstellt Hochstellung

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Hochstellung (obere Index rechts) |

### Rückgabewert

Neues Mathelement vom Typ [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Bemerkungen



Beispiel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)