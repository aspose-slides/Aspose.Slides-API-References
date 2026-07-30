---
title: AddFallBackFonts()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Přidá nové písmo(písma) do seznamu záložních písem.
type: docs
weight: 79
url: /cs/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) metoda

Přidá nové písmo(písma) do seznamu záložních písem.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Název písma nebo názvy (oddělené čárkou) pro záložní písmo |
## Poznámky

```cpp
// Vytvořte novou instanci FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Přidejte druhé písmo do pravidla
newRule->AddFallBackFonts(u"MS Gothic");
//Přidejte třetí a čtvrté písma do pravidla
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) metoda

Přidá nová písma do seznamu záložních písem.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Název písma nebo názvy (oddělené čárkou) pro záložní písmo |
## Poznámky

```cpp
//Vytvořte novou instanci FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Přidejte další tři písma do pravidla
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Třída [String](../../../system/string/)
* Třída [FontFallBackRule](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)