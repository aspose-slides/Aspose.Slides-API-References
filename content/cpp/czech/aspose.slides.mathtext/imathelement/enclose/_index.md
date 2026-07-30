---
title: Enclose()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Uzavře matematický prvek do závorek
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() metoda


Uzavře matematický prvek do závorek

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```


### Návratová hodnota

Matematický prvek typu [IMathDelimiter](../../imathdelimiter/) který zahrnuje závorky
## Poznámky



Příklad:
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) metoda


Uzavře tento prvek do zadaných znaků, například do závorek nebo jiných znaků jako ohraničení

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| beginningCharacter | char16_t | Počáteční znak (obvykle levá závorka) |
| endingCharacter | char16_t | Koncový znak (obvykle pravá závorka) |

### Návratová hodnota

Matematický prvek typu [IMathDelimiter](../../imathdelimiter/) který zahrnuje zadané znaky jako ohraničení
## Poznámky



Příklad:
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathDelimiter](../../imathdelimiter/)
* Třída [IMathElement](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)