---
title: idx_get()
second_title: Aspose.Slides C++ API referencia
description: A megadott indexen lévő szabályt adja vissza. Csak olvasható IFontFallBackRule.
type: docs
weight: 1
url: /hu/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) method

Az adott indexen lévő szabályt adja vissza. Csak olvasható [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## Megjegyzés

```cpp
auto pres = MakeObject<Presentation>();
//Üres vagy előre inicializált szabálygyűjtemény lekérése a FontsManager-ből
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Több szabály hozzáadása a gyűjteményhez
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Az első szabály objektumának lekérése a gyűjteményből
auto firstRule = rulesList->idx_get(0);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IFontFallBackRule](../../ifontfallbackrule/)
* Osztály [IFontFallBackRulesCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)