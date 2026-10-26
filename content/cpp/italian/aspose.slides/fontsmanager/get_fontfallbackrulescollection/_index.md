---
title: get_FontFallBackRulesCollection()
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta la raccolta di regole FontFallBack di un utente per la gestione delle collezioni di font per le sostituzioni corrette tramite la funzionalità di fallback. Leggi IFontFallBackRulesCollection.
type: docs
weight: 27
url: /it/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() metodo

Rappresenta la raccolta di regole FontFallBack di un utente per la gestione delle collezioni di font per le sostituzioni corrette tramite la funzionalità di fallback. Leggi [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## Note


```cpp
auto pres = MakeObject<Presentation>();
// Ottenimento della raccolta di regole vuota o preinizializzata da FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// aggiunta di regole alla raccolta
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// oppure
// inizializzazione di una nuova istanza della raccolta di regole
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// aggiunta di regole alla raccolta
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// e sostituzione della raccolta esistente con quella nuova in FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Classe [FontsManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)