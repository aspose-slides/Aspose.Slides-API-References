---
title: SetSubscript()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt Tiefstellung
type: docs
weight: 66
url: /de/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) Methode

Erstellt Tiefstellung

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Tiefstellung (unterer Index rechts) |

### Rückgabewert

Neues Math-Element vom Typ [IMathSubscriptElement](../../imathsubscriptelement/)
## Bemerkungen



Beispiel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) Methode

Erstellt Tiefstellung

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Tiefstellung (unterer Index rechts) |

### Rückgabewert

Neues Math-Element vom Typ [IMathSubscriptElement](../../imathsubscriptelement/)
## Bemerkungen



Beispiel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathSubscriptElement](../../imathsubscriptelement/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)