---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides C++ API hivatkozás
description: A felhasználó FontFallBack szabályainak gyűjteményét jelenti, amely a betűkészletek gyűjteményeinek kezelésére szolgál a fallback funkció megfelelő helyettesítéseihez. Write IFontFallBackRulesCollection.
type: docs
weight: 40
url: /hu/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) módszer


A felhasználó FontFallBack szabályainak gyűjteményét képviseli a betűkészletek gyűjteményeinek kezelésére a fallback funkcióval való megfelelő helyettesítések érdekében. Írja [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## Megjegyzés



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
// és a meglévő gyűjtemény cseréje az újra a FontsManager-ben
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Osztály [IFontsManager](../)
* Névtere [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)