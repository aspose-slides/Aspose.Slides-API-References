---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides C++ API referenciája
description: Representálja a felhasználó FontFallBack szabályainak gyűjteményét a betűkészletek gyűjteményeinek kezelésére, a megfelelő helyettesítések érdekében a fallback funkcióval. Olvassa IFontFallBackRulesCollection.
type: docs
weight: 27
url: /hu/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() metódus

Representálja a felhasználó FontFallBack szabályainak gyűjteményét a betűkészletek gyűjteményeinek kezelésére a megfelelő helyettesítésekhez a fallback funkcióval. Olvassa el [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
```

## Megjegyzések

```cpp
auto pres = MakeObject<Presentation>();
// Az üres vagy előre inicializált szabálykészlet lekérése a FontsManager-ből
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// szabályok hozzáadása a gyűjteményhez
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
 // vagy
 // új szabálykészlet példányának inicializálása
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// szabályok hozzáadása a gyűjteményhez
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// és a meglévő gyűjtemény cseréje az újjal a FontsManager-ben
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Osztály [IFontsManager](../)
* Névterület [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)