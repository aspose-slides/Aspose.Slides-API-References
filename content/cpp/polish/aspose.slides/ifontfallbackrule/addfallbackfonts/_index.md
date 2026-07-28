---
title: AddFallBackFonts()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Dodaje nową czcionkę (lub czcionki) do listy czcionek FallBack.
type: docs
weight: 40
url: /pl/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) metoda

Dodaje nową czcionkę (lub czcionki) do listy czcionek FallBack.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nazwa lub nazwy czcionki (oddzielone przecinkiem) dla FallBack |

## Uwagi

```cpp
//Utworzenie nowej instancji FantFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Dodaj drugą czcionkę do reguły
newRule->AddFallBackFonts(u"MS Gothic");
//Dodaj trzecią i czwartą czcionkę do reguły
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) metoda

Dodaje nowe czcionki do listy czcionek FallBack.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nazwa lub nazwy czcionki (oddzielone przecinkiem) dla FallBack |

## Uwagi

```cpp
//Utworzenie nowej instancji FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Dodanie kolejnych trzech czcionek do reguły
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Zobacz również

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [IFontFallBackRule](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)