---
title: SetSubscript()
second_title: Aspose.Slides för C++ API-referens
description: Skapar nedsänkt tecken
type: docs
weight: 66
url: /sv/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) metod


Skapar nedsänkt

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Nedsänkt (lägre index på högra sidan) |

### Returvärde

Nytt matematiskt element av typen [IMathSubscriptElement](../../imathsubscriptelement/)
## Anmärkningar



Exempel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) metod


Skapar nedsänkt
```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Nedsänkt (lägre index till höger) |

### Returvärde

Nytt matematiskt element av typ [IMathSubscriptElement](../../imathsubscriptelement/)
## Anmärkningar



Exempel: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathSubscriptElement](../../imathsubscriptelement/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathElementBase](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)