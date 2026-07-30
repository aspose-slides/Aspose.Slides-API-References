---
title: Add()
second_title: Aspose.Slides pro C++ referenci API
description: Přidá nové pravidlo FallBack na konec kolekce.
type: docs
weight: 14
url: /cs/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) metoda

Přidejte nové pravidlo FallBack na konec kolekce.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Určené pravidlo pro přidání |

## Poznámky

```cpp
auto pres = MakeObject<Presentation>();
//Získání prázdné nebo předinicializované kolekce pravidel z FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Přidání nového pravidla do kolekce
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IFontFallBackRule](../../ifontfallbackrule/)
* Třída [IFontFallBackRulesCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)