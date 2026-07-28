---
title: idx_get()
second_title: Aspose.Slides C++ API referenciája
description: Lekéri a szabályt a megadott indexnél. Csak-olvasás IFontFallBackRule.
type: docs
weight: 66
url: /hu/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) metódus

Lekéri a szabályt a megadott indexnél. Csak-olvasás [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
```

## Megjegyzések



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

* Typedef [SharedPtr](../../../system/sharedptr/)
* osztály [IFontFallBackRule](../../ifontfallbackrule/)
* osztály [FontFallBackRulesCollection](../)
* névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)