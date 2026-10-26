---
title: FontFallBackRule()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Instanz.
type: docs
weight: 66
url: /de/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) Konstruktor

Erstellt eine neue Instanz.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | **uint32_t** | Startindex des Unicode-Bereichs |
| endIndex | **uint32_t** | Endindex des Unicode-Bereichs |
| fontNames | [System::String](../../../system/string/) | Name oder Namen der Schrift (durch Komma getrennt) für FallBack |
## Bemerkungen

```cpp
// Erstelle eine neue Instanz von FantFallBackRule mit einer Schriftart.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// Erstelle eine neue Instanz von FantFallBackRule mit mehreren Schriftarten.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```

## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) Konstruktor

Erstellt eine neue Instanz.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | **uint32_t** | Startindex des Unicode-Bereichs |
| endIndex | **uint32_t** | Endindex des Unicode-Bereichs |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Name oder Namen der Schrift (durch Komma getrennt) für FallBack |
## Bemerkungen

```cpp
// Erstelle eine neue Instanz von FantFallBackRule mit zwei Schriftarten
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// Erstelle eine neue Instanz von FantFallBackRule mit mehreren Schriftarten.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [FontFallBackRule](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)