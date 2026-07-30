---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides per C++ Riferimento API
description: Rappresenta la raccolta dell'utente di regole FontFallBack per la gestione delle collezioni di caratteri per le corrette sostituzioni mediante la funzionalità di fallback Scrivi IFontFallBackRulesCollection.
type: docs
weight: 40
url: /it/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) metodo

Rappresenta la raccolta dell'utente di regole FontFallBack per la gestione delle collezioni di caratteri per le corrette sostituzioni tramite la funzionalità di fallback Scrivi [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## Osservazioni

```cpp
auto pres = MakeObject<Presentation>();
// Ottenimento della collezione di regole vuota o preinizializzata da FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// Aggiunta di regole alla collezione
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// oppure
// Inizializzazione di una nuova istanza della collezione di regole
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// Aggiunta di regole alla collezione
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// e sostituzione della collezione esistente con quella nuova in FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Classe [FontsManager](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)