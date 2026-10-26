---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides pro C++ API Reference
description: Reprezentuje uživatelskou kolekci pravidel FontFallBack pro správu kolekcí písem pro správné nahrazení pomocí fallback funkce. Přečtěte si IFontFallBackRulesCollection.
type: docs
weight: 27
url: /cs/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() metoda


Reprezentuje uživatelskou kolekci pravidel FontFallBack pro správu kolekcí písem pro správné nahrazení pomocí fallback funkce. Přečtěte si [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
```

## Poznámky



```cpp
auto pres = MakeObject<Presentation>();
// Získání prázdné nebo předinicializované kolekce pravidel z FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// přidání pravidel do kolekce
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// nebo
// inicializace nové instance kolekce pravidel
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// přidání pravidel do kolekce
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// a nahrazení existující kolekce novou v FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Třída [IFontsManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)