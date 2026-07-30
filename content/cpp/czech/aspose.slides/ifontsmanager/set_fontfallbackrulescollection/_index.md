---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Reprezentuje uživatelskou kolekci pravidel FontFallBack pro správu kolekcí fontů pro správné náhrady pomocí fallback funkčnosti Zapište IFontFallBackRulesCollection.
type: docs
weight: 40
url: /cs/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) metoda


Reprezentuje uživatelskou sbírku pravidel FontFallBack pro správu kolekcí fontů pro správné náhrady pomocí fallback funkce Zapište [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
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
* Library [Aspose.Slides](../../../)