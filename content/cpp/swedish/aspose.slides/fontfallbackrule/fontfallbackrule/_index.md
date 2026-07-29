---
title: FontFallBackRule()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans.
type: docs
weight: 66
url: /sv/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) konstruktor


Skapar en ny instans.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | **uint32_t** | Startindex för unicode-intervall |
| endIndex | **uint32_t** | Slutindex för unicode-intervall |
| fontNames | [System::String](../../../system/string/) | Fontens namn eller namn (avgränsade med kommatecken) för FallBack |
## Anmärkningar



```cpp
// Skapa en ny instans av FantFallBackRule med ett teckensnitt.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// Skapa en ny instans av FantFallBackRule med flera teckensnitt.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```


## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) konstruktor


Skapar en ny instans.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | **uint32_t** | Startindex för unicode-intervall |
| endIndex | **uint32_t** | Slutindex för unicode-intervall |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Fontens namn eller namn (avgränsade med kommatecken) för FallBack |
## Anmärkningar



```cpp
// Skapa en ny instans av FantFallBackRule med två teckensnitt
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// Skapa en ny instans av FantFallBackRule med flera teckensnitt.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [FontFallBackRule](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)