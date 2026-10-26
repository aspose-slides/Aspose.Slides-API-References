---
title: Remove()
second_title: Aspose.Slides C++ API-referencia
description: Eltávolítja a gyűjteményből egy adott FallBack szabály első előfordulását.
type: docs
weight: 27
url: /hu/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) method

Eltávolítja a megadott FallBack szabály első előfordulását a gyűjteményből.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | A szabály, amelyet el kell távolítani a gyűjteményből. |
## Megjegyzések



```cpp
auto pres = MakeObject<Presentation>();
//A FontsManager-től egy üres vagy előre inicializált szabálygyűjtemény lekérése
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Több szabály hozzáadása a gyűjteményhez
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Az első szabály objektumának lekérése a gyűjteményből
auto firstRule = rulesList->idx_get(0);
//Eltávolítás
rulesList->Remove(firstRule);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IFontFallBackRule](../../ifontfallbackrule/)
* Osztály [IFontFallBackRulesCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)