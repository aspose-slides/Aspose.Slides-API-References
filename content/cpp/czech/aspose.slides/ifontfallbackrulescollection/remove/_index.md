---
title: Remove()
second_title: Aspose.Slides pro C++ – reference API
description: Odstraňuje první výskyt konkrétního pravidla FallBack ze sbírky.
type: docs
weight: 27
url: /cs/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) metoda

Odstraňuje první výskyt konkrétního pravidla FallBack ze sbírky.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule)=0
```

### Argumenty

| Parameter | Type | Description |
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
* třída [IFontFallBackRule](../../ifontfallbackrule/)
* třída [IFontFallBackRulesCollection](../)
* jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)