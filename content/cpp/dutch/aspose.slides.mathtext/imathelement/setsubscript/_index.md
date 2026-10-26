---
title: SetSubscript()
second_title: Aspose.Slides voor C++ API Referentie
description: Maakt subscript
type: docs
weight: 79
url: /nl/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) methode

Maakt subscript

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subscript (lagere index aan de rechterkant) |

### Retourwaarde

Nieuw wiskundig element van type [IMathSubscriptElement](../../imathsubscriptelement/)

## Opmerkingen

Voorbeeld: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) methode

Maakt subscript

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscript (lagere index aan de rechterkant) |

### Retourwaarde

Nieuw wiskundig element van type [IMathSubscriptElement](../../imathsubscriptelement/)

## Opmerkingen

Voorbeeld: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathSubscriptElement](../../imathsubscriptelement/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)