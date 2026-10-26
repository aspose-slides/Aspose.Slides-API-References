---
title: Remove()
second_title: Aspose.Slides C++ API referencia
description: Eltávolítja egy adott FallBack szabály első előfordulását a gyűjteményből.
type: docs
weight: 53
url: /hu/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) metódus


Eltávolítja egy adott FallBack szabály első előfordulását a gyűjteményből.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | A szabály, amelyet el kell távolítani a gyűjteményből. |
## Megjegyzések



```cpp
auto pres = MakeObject<Presentation>();
//Az üres vagy előre inicializált szabálygyűjtemény lekérése a FontsManager-ből
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
* Osztály [FontFallBackRulesCollection](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)