---
title: Enclose()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Obaluje matematický prvek ve specifikovaných znacích, například závorkami nebo jinými znaky jako rámování
type: docs
weight: 170
url: /cs/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) metoda

Obaluje matematický prvek ve specifikovaných znacích, například závorkami nebo jinými znaky jako rámování

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| beginningCharacter | char16_t | Počáteční znak (obvykle levá závorka) |
| endingCharacter | char16_t | Koncový znak (obvykle pravá závorka) |

### Návratová hodnota

Pokud jsou *beginningCharacter* a *endingCharacter* null, odpovídající vlastnosti jsou pouze přiřazeny hodnoty a není vytvořen nový objekt (vrací tuto instanci). Jinak vrací nový matematický prvek typu Delimiter, který zahrnuje zadané znaky jako rámování a tuto instanci [MathDelimiter](../) uvnitř rámce.

## Poznámky

Příklad:
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IMathDelimiter](../../imathdelimiter/)
* Třída [MathDelimiter](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)