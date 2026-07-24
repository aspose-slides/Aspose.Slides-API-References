---
title: SetSubscript()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt Tiefstellung
type: docs
weight: 79
url: /de/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) Methode


Erstellt Tiefstellung

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Tiefstellung (unterer Index auf der rechten Seite) |

### Rückgabewert

Neues Mathe-Element vom Typ [IMathSubscriptElement](../../imathsubscriptelement/)
## Bemerkungen



Beispiel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) Methode


Erstellt Tiefstellung

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Tiefstellung (unterer Index auf der rechten Seite) |

### Rückgabewert

Neues Mathe-Element vom Typ [IMathSubscriptElement](../../imathsubscriptelement/)
## Bemerkungen



Beispiel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathSubscriptElement](../../imathsubscriptelement/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)