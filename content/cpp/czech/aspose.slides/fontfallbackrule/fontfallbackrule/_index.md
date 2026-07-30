---
title: FontFallBackRule()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří novou instanci.
type: docs
weight: 66
url: /cs/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) konstruktor


Vytvoří novou instanci.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | **uint32_t** | Počáteční index rozsahu Unicode |
| endIndex | **uint32_t** | Koncový index rozsahu Unicode |
| fontNames | [System::String](../../../system/string/) | Název nebo názvy fontu (oddělené čárkou) pro FallBack |
## Poznámky



```cpp
// Vytvoří novou instanci FantFallBackRule s jedním fontem.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// Vytvoří novou instanci FantFallBackRule s několika fonty.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```


## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) konstruktor


Vytvoří novou instanci.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| startIndex | **uint32_t** | Počáteční index rozsahu Unicode |
| endIndex | **uint32_t** | Koncový index rozsahu Unicode |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Název nebo názvy fontu (oddělené čárkou) pro FallBack |
## Poznámky



```cpp
// Vytvoří novou instanci FantFallBackRule se dvěma fonty
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// Vytvoří novou instanci FantFallBackRule s několika fonty.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [FontFallBackRule](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)