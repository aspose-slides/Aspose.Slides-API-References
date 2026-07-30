---
title: Remove()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove la prima occorrenza di una regola FallBack specifica dalla collezione.
type: docs
weight: 53
url: /it/aspose.slides/fontfallbackrulescollection/remove/
---
## FontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) metodo

Rimuove la prima occorrenza di una regola FallBack specifica dalla collezione.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | La regola da rimuovere dalla collezione. |
## Osservazioni

```cpp
auto pres = MakeObject<Presentation>();
//Ottenimento della collezione di regole vuota o preinizializzata da FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Aggiunta di diverse regole alla collezione
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Recupero dell'oggetto della prima regola nella collezione
auto firstRule = rulesList->idx_get(0);
//Rimozione
rulesList->Remove(firstRule);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRule](../../ifontfallbackrule/)
* Classe [FontFallBackRulesCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)