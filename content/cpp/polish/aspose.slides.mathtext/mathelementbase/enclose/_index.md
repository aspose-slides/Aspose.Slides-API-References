---
title: Enclose()
second_title: Aspose.Slides dla C++ – Odniesienie API
description: Otacza element matematyczny w nawiasie
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() metoda


Otacza element matematyczny nawiasami

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```


### Wartość zwracana

Element matematyczny typu [IMathDelimiter](../../imathdelimiter/) zawierający nawiasy
## Uwagi



Przykład: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) metoda


Otacza element matematyczny określonymi znakami, takimi jak nawiasy lub innymi znakami jako ramka

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| beginningCharacter | char16_t | Znak początkowy (zwykle lewy nawias) |
| endingCharacter | char16_t | Znak końcowy (zwykle prawy nawias) |

### Wartość zwracana

Element matematyczny typu [IMathDelimiter](../../imathdelimiter/) zawierający określone znaki jako ramkę
## Uwagi



Przykład: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)