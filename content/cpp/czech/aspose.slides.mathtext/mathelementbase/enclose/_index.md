---
title: Enclose()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Obalí matematický prvek v závorkách
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() metoda


Obaluje matematický prvek v závorkách

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```


### Návratová hodnota

Matematický prvek typu [IMathDelimiter](../../imathdelimiter/), který zahrnuje závorky
## Poznámky



Příklad: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) metoda


Obaluje matematický prvek ve specifikovaných znacích, například v závorkách nebo jiných znacích jako ohraničení

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| beginningCharacter | char16_t | Počáteční znak (obvykle levá závorka) |
| endingCharacter | char16_t | Koncový znak (obvykle pravá závorka) |

### Návratová hodnota

Matematický prvek typu [IMathDelimiter](../../imathdelimiter/), který zahrnuje specifikované znaky jako ohraničení
## Poznámky



Příklad: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathDelimiter](../../imathdelimiter/)
* Třída [MathElementBase](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)