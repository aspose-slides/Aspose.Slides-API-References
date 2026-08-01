---
title: FontFallBackRule()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw exemplaar aan.
type: docs
weight: 66
url: /nl/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) constructor

Maakt een nieuw exemplaar aan.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | **uint32_t** | Beginindex van het Unicode-bereik |
| endIndex | **uint32_t** | Eindindex van het Unicode-bereik |
| fontNames | [System::String](../../../system/string/) | Naam of namen van het lettertype (gescheiden door komma) voor FallBack |
## Opmerkingen

```cpp
// Maak een nieuw exemplaar van FantFallBackRule met één lettertype.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// Maak een nieuw exemplaar van FantFallBackRule met meerdere lettertypen.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```

## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) constructor

Maakt een nieuw exemplaar aan.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | **uint32_t** | Beginindex van het Unicode-bereik |
| endIndex | **uint32_t** | Eindindex van het Unicode-bereik |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Naam of namen van het lettertype (gescheiden door komma) voor FallBack |
## Opmerkingen

```cpp
// Maak een nieuw exemplaar van FantFallBackRule met twee lettertypen
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// Maak een nieuw exemplaar van FantFallBackRule met meerdere lettertypen.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [FontFallBackRule](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)