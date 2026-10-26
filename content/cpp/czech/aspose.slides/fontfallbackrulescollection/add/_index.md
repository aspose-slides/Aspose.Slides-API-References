---
title: Add()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Přidá určené pravidlo FallBack na konec kolekce.
type: docs
weight: 40
url: /cs/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) metoda

Přidá určené pravidlo fallback na konec kolekce.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Určené pravidlo pro přidání |
## Poznámky



```cpp
auto pres = MakeObject<Presentation>();
//Získání prázdné nebo předinicializované kolekce pravidel z FontsManageru
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Přidání nového pravidla do kolekce
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```


## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IFontFallBackRule](../../ifontfallbackrule/)
* Třída [FontFallBackRulesCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)