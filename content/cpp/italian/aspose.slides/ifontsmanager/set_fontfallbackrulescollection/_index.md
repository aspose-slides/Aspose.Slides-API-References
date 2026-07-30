---
title: set_FontFallBackRulesCollection()
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta la raccolta di regole FontFallBack di un utente per la gestione di collezioni di caratteri per le corrette sostituzioni mediante la funzionalità di fallback. Scrivi IFontFallBackRulesCollection.
type: docs
weight: 40
url: /it/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) metodo


Rappresenta la raccolta di regole FontFallBack di un utente per la gestione di raccolte di caratteri per le corrette sostituzioni mediante la funzionalità di fallback. Scrivi [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## Osservazioni



```cpp
auto pres = MakeObject<Presentation>();
// Ottenimento della collezione di regole vuota o preinizializzata da FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// aggiunta di regole alla collezione
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// o
// inizializzazione di una nuova istanza della collezione di regole
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// aggiunta di regole alla collezione
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// e sostituzione della collezione esistente con quella nuova in FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Class [IFontsManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)