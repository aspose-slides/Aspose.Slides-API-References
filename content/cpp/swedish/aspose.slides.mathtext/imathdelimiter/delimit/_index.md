---
title: Delimit()
second_title: Aspose.Slides för C++ API-referens
description: Avgränsar argument med det angivna avgränsningstecknet
type: docs
weight: 144
url: /sv/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) metod


Avgränsar argument med det angivna avgränsningstecknet

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| separatorCharacter | char16_t | avgränsningstecken |

### Returvärde

Det här objektet efter att ha tillämpat avgränsningstecknet
## Anmärkningar



Exempel: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [IMathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)