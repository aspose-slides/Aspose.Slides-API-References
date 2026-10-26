---
title: AddFallBackFonts()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt neue Schriftart(en) zur Liste der FallBack-Schriftarten hinzu.
type: docs
weight: 79
url: /de/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) Methode

Fügt neue Schriftart(en) zur Liste der FallBack-Schriftarten hinzu.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Name oder Namen der Schriftart (durch Komma getrennt) für FallBack |

## Anmerkungen

```cpp
// Neue Instanz von FontFallBackRule erstellen
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Füge eine zweite Schriftart zur Regel hinzu
newRule->AddFallBackFonts(u"MS Gothic");
//Füge eine dritte und vierte Schriftart zur Regel hinzu
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) Methode

Fügt neue Schriftarten zur Liste der FallBack-Schriftarten hinzu.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Name oder Namen der Schriftart (durch Komma getrennt) für FallBack |

## Anmerkungen

```cpp
//Neue Instanz von FontFallBackRule erstellen
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Füge weitere drei Schriftarten zur Regel hinzu
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [FontFallBackRule](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)