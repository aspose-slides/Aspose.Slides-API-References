---
title: Remove()
second_title: Aspose.Slides pro C++ – reference API
description: Odstraňuje první výskyt konkrétního pravidla FallBack ze sbírky.
type: docs
weight: 53
url: /cs/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) metoda

Odstraňuje první výskyt konkrétního pravidla FallBack ze sbírky.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Pravidlo, které se má odstranit ze sbírky. |

## Poznámky

```cpp
auto pres = MakeObject<Presentation>();
//Získání prázdné nebo předinicializované kolekce pravidel z FontsManageru
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Přidání několika pravidel do kolekce
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Získání objektu prvního pravidla v kolekci
auto firstRule = rulesList->idx_get(0);
//Odstranění
rulesList->Remove(firstRule);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IFontFallBackRule](../../ifontfallbackrule/)
* Třída [FontFallBackRulesCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)