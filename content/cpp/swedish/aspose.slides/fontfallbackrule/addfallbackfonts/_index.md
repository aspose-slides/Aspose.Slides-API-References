---
title: AddFallBackFonts()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till ett nytt teckensnitt (eller flera) i listan över FallBack-teckensnitt.
type: docs
weight: 79
url: /sv/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) metod


Lägger till ett nytt teckensnitt (eller flera) i listan över FallBack-teckensnitt.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Teckensnittets namn eller namn (avgränsade med kommatecken) för FallBack |
## Anmärkningar



```cpp
// Skapa ny instans av FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Lägg till ett andra teckensnitt i regeln
newRule->AddFallBackFonts(u"MS Gothic");
//Lägg till ett tredje och fjärde teckensnitt i regeln
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```


## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) metod


Lägger till nya teckensnitt i listan över FallBack-teckensnitt.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Teckensnittets namn eller namn (avgränsade med kommatecken) för FallBack |
## Anmärkningar



```cpp
//Skapa ny instans av FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Lägg till ytterligare tre teckensnitt i regeln
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [FontFallBackRule](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)