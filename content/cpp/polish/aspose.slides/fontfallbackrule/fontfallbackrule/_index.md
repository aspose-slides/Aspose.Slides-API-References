---
title: FontFallBackRule()
second_title: Aspose.Slides dla C++ – referencja API
description: Tworzy nową instancję.
type: docs
weight: 66
url: /pl/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) konstruktor


Tworzy nową instancję.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | **uint32_t** | Początkowy indeks zakresu Unicode |
| endIndex | **uint32_t** | Końcowy indeks zakresu Unicode |
| fontNames | [System::String](../../../system/string/) | Nazwa lub nazwy czcionki (oddzielone przecinkami) dla FallBack |
## Uwagi



```cpp
// Utwórz nową instancję FantFallBackRule z jedną czcionką.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// Utwórz nową instancję FantFallBackRule z kilkoma czcionkami.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```


## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) konstruktor


Tworzy nową instancję.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| startIndex | **uint32_t** | Początkowy indeks zakresu Unicode |
| endIndex | **uint32_t** | Końcowy indeks zakresu Unicode |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Nazwa lub nazwy czcionki (oddzielone przecinkami) dla FallBack |
## Uwagi



```cpp
// Utwórz nową instancję FantFallBackRule z dwoma czcionkami
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// Utwórz nową instancję FantFallBackRule z kilkoma czcionkami.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasa [String](../../../system/string/)
* Klasa [FontFallBackRule](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)