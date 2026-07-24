---
title: SetSuperscript()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt Hochstellung
type: docs
weight: 92
url: /de/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) Methode


Erstellt Hochstellung

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Hochstellung (obere Index rechts) |

### Rückgabewert

Neues mathematisches Element vom Typ [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Bemerkungen



Beispiel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) Methode


Erstellt Hochstellung

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Hochstellung (obere Index rechts) |

### Rückgabewert

Neues mathematisches Element vom Typ [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Bemerkungen



Beispiel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)