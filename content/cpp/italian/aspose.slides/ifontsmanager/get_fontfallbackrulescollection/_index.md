---
title: get_FontFallBackRulesCollection()
second_title: Riferimento API di Aspose.Slides per C++
description: Rappresenta la raccolta dell'utente di regole FontFallBack per la gestione delle collezioni di caratteri per le sostituzioni corrette tramite la funzionalità di fallback. Leggi IFontFallBackRulesCollection.
type: docs
weight: 27
url: /it/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() metodo


Rappresenta la raccolta dell'utente di regole FontFallBack per la gestione delle raccolte di caratteri per le sostituzioni corrette tramite la funzionalità di fallback. Leggi [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
```

## Osservazioni


```cpp
auto pres = MakeObject<Presentation>();
// Ottenimento della collezione di regole vuota o preinizializzata da FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// aggiunta di regole alla collezione
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// oppure
// inizializzazione di una nuova istanza della collezione di regole
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// aggiunta di regole alla collezione
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// e sostituzione della collezione esistente con quella nuova in FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Classe [IFontsManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)