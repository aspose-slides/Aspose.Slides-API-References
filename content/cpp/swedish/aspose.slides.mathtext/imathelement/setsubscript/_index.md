---
title: SetSubscript()
second_title: Aspose.Slides för C++ API-referens
description: Skapar nedsänkt
type: docs
weight: 79
url: /sv/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) metod


Skapar nedsänkt

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Nedsänkt (lägre index till höger) |

### Return Value

Nytt matematiskt element av typen [IMathSubscriptElement](../../imathsubscriptelement/)
## Anmärkningar



Exempel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) metod


Skapar nedsänkt

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Nedsänkt (lägre index till höger) |

### Return Value

Nytt matematiskt element av typen [IMathSubscriptElement](../../imathsubscriptelement/)
## Anmärkningar



Exempel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathSubscriptElement](../../imathsubscriptelement/)
* Klass [IMathElement](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)