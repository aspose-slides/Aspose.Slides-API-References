---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides C++ API referenciája
description: Egy felhasználó FontFallBack szabálykészletét képviseli a betűtípusok gyűjteményeinek kezeléséhez, a helyes helyettesítéseket biztosító fallback funkcióval. Olvassa IFontFallBackRulesCollection.
type: docs
weight: 27
url: /hu/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() metódus


Egy felhasználó FontFallBack szabálykészletét képviseli a betűtípusok gyűjteményeinek kezeléséhez, hogy a fallback funkció megfelelő helyettesítéseket végezzen. Olvassa [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## Megjegyzések



```cpp
auto pres = MakeObject<Presentation>();
// A FontsManager-től üres vagy előre inicializált szabálykészlet lekérése
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// szabályok hozzáadása a gyűjteményhez
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
 // vagy
 // új szabálykészlet példányának inicializálása
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// szabályok hozzáadása a gyűjteményhez
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// a meglévő gyűjtemény cseréje az újra a FontsManager-ben
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Class [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)