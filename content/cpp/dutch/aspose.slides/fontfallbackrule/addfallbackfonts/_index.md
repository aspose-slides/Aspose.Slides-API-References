---
title: AddFallBackFonts()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een nieuw lettertype(s) toe aan de lijst met fallback-lettertypen.
type: docs
weight: 79
url: /nl/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) method

Voegt nieuwe lettertype(s) toe aan de lijst met fallback-lettertypen.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Font's name or names (delimited by comma) for FallBack |
## Opmerkingen

```cpp
// Maak een nieuw exemplaar van FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Voeg een tweede lettertype toe aan de regel
newRule->AddFallBackFonts(u"MS Gothic");
//Voeg een derde en vierde lettertypen toe aan de regel
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) method

Voegt nieuwe lettertypen toe aan de lijst met fallback-lettertypen.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Font's name or names (delimited by comma) for FallBack |
## Opmerkingen

```cpp
//Maak een nieuw exemplaar van FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Voeg nog drie lettertypen toe aan de regel
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)