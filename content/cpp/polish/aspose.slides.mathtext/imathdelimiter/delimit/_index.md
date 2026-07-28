---
title: Delimit()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Rozdziela argumenty przy użyciu określonego znaku separatora
type: docs
weight: 144
url: /pl/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) metoda

Rozdziela argumenty przy użyciu określonego znaku separatora

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| separatorCharacter | char16_t | znak separatora |

### Wartość zwracana

Ten obiekt po zastosowaniu znaku separatora
## Uwagi



Przykład: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)