---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Reprezentuje uživatelovu kolekci pravidel FontFallBack pro správu sbírek fontů a pro správná nahrazování pomocí funkce náhrad. Přečtěte si IFontFallBackRulesCollection.
type: docs
weight: 27
url: /cs/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() metoda


Reprezentuje uživatelovu kolekci pravidel FontFallBack pro správu sbírek fontů a pro správná nahrazování pomocí funkce náhrad. Přečtěte si [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
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
* Třída [FontsManager](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)