---
title: AddFallBackFonts()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till nya teckensnitt till listan med FallBack-teckensnitt.
type: docs
weight: 40
url: /sv/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) metod

Lägger till nya teckensnitt till listan med FallBack-teckensnitt.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Teckensnittets namn eller namn (avgränsade med kommatecken) för FallBack |
## Anmärkningar



```cpp
//Skapa en ny instans av FantFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Lägg till ett andra teckensnitt till regeln
newRule->AddFallBackFonts(u"MS Gothic");
//Lägg till ett tredje och fjärde teckensnitt till regeln
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) metod

Lägger till nya teckensnitt till listan med FallBack-teckensnitt.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Teckensnittets namn eller namn (avgränsade med kommatecken) för FallBack |
## Anmärkningar



```cpp
//Skapa en ny instans av FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Lägg till ytterligare tre teckensnitt till regeln
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [IFontFallBackRule](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)