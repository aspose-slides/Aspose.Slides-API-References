---
title: Delimit()
second_title: Aspose.Slides pro C++ - reference API
description: Odděluje argumenty pomocí zadaného znaku oddělovače
type: docs
weight: 144
url: /cs/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) metoda


Odděluje argumenty pomocí zadaného znaku oddělovače

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| separatorCharacter | char16_t | znak oddělovače |

### Návratová hodnota

Tento objekt po použití znaku oddělovače
## Poznámky



Příklad: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IMathDelimiter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)