---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides C++ API referenciája
description: Egy felhasználó FontFallBack szabályainak gyűjteményét képviseli a betűtípus-gyűjtemények kezelésére a megfelelő helyettesítések biztosításához a visszaeső funkcióval. Írja IFontFallBackRulesCollection.
type: docs
weight: 40
url: /hu/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) metódus


Egy felhasználó FontFallBack szabályainak gyűjteményét képviseli a betűtípus-gyűjtemények kezelésére a megfelelő helyettesítések biztosításához a visszaeső funkcióval. Írja [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## Megjegyzések



```cpp
auto pres = MakeObject<Presentation>();
// Üres vagy előre inicializált szabálygyűjtemény lekérése a FontsManager-ből
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// szabályok hozzáadása a gyűjteményhez
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// vagy
// új szabálygyűjtemény példányának inicializálása
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// szabályok hozzáadása a gyűjteményhez
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// és a meglévő gyűjtemény helyettesítése az újjával a FontsManager-ben
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Osztály [FontsManager](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)