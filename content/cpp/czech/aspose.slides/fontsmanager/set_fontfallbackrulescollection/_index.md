---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Představuje uživatelovu kolekci pravidel FontFallBack pro správu kolekcí fontů pro správné náhrady pomocí fallback funkce. Zapište IFontFallBackRulesCollection.
type: docs
weight: 40
url: /cs/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) metoda

Představuje uživatelovu kolekci pravidel FontFallBack pro správu kolekcí fontů pro správné náhrady pomocí fallback funkce Zapište [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
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