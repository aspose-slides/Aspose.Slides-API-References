---
title: AddFallBackFonts()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Přidá nový font(y) do seznamu náhradních fontů.
type: docs
weight: 40
url: /cs/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) metoda


Přidá nový font(y) do seznamu náhradních fontů.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Font's name or names (delimited by comma) for FallBack |
## Poznámky



```cpp
//Vytvoření nové instance FantFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Přidá druhý font do pravidla
newRule->AddFallBackFonts(u"MS Gothic");
//Přidá třetí a čtvrtý fonty do pravidla
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```


## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) metoda


Přidá nové fonty do seznamu náhradních fontů.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Font's name or names (delimited by comma) for FallBack |
## Poznámky



```cpp
//Vytvoření nové instance FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Přidání dalších tří fontů do pravidla
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [IFontFallBackRule](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)