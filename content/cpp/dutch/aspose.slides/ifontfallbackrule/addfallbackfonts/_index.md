---
title: AddFallBackFonts()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een nieuw(lettertype) toe aan de lijst met FallBack-lettertypen.
type: docs
weight: 40
url: /nl/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) methode


Voegt een nieuw(lettertype(s)) toe aan de lijst met FallBack-lettertypen.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Naam of namen van het lettertype (gescheiden door komma) voor FallBack |
## Opmerkingen



```cpp
//Creëer een nieuw exemplaar van FantFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Voeg een tweede lettertype toe aan de regel
newRule->AddFallBackFonts(u"MS Gothic");
//Voeg een derde en vierde lettertype toe aan de regel
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```


## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) methode


Voegt nieuwe lettertypen toe aan de lijst met FallBack-lettertypen.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Naam of namen van het lettertype (gescheiden door komma) voor FallBack |
## Opmerkingen



```cpp
//Creëer een nieuw exemplaar van FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Voeg nog drie lettertypen toe aan de regel
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [IFontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)