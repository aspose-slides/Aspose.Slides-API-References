---
title: AddFallBackFonts()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt eine(n) neue(s) Schriftart(en) zur Liste der FallBack-Schriften hinzu.
type: docs
weight: 40
url: /de/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) Methode

Fügt eine(n) neue(s) Schriftart(en) zur Liste der FallBack-Schriften hinzu.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Name oder Namen der Schriftart (durch Komma getrennt) für FallBack |
## Hinweise



```cpp
//Erstelle neue Instanz von FantFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Füge eine zweite Schriftart zur Regel hinzu
newRule->AddFallBackFonts(u"MS Gothic");
//Füge dritte und vierte Schriftarten zur Regel hinzu
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) Methode

Fügt neue Schriftarten zur Liste der FallBack-Schriften hinzu.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Name oder Namen der Schriftart (durch Komma getrennt) für FallBack |
## Hinweise



```cpp
//Erstelle eine neue Instanz von FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Füge drei weitere Schriftarten zur Regel hinzu
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [IFontFallBackRule](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)