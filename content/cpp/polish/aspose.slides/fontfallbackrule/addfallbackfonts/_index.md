---
title: AddFallBackFonts()
second_title: Aspose.Slides dla C++ API Reference
description: Dodaje nową czcionkę(-e) do listy czcionek FallBack.
type: docs
weight: 79
url: /pl/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) metoda

Dodaje nową czcionkę(-e) do listy czcionek FallBack.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nazwa lub nazwy czcionki (oddzielone przecinkami) dla FallBack |
## Uwagi

```cpp
// Utwórz nową instancję FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Dodaj drugą czcionkę do reguły
newRule->AddFallBackFonts(u"MS Gothic");
//Dodaj trzecią i czwartą czcionkę do reguły
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) metoda

Dodaje nowe czcionki do listy czcionek FallBack.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nazwy czcionek (oddzielone przecinkami) dla FallBack |
## Uwagi

```cpp
//Utwórz nową instancję FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Dodaj kolejne trzy czcionki do reguły
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [FontFallBackRule](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)