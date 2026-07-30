---
title: Add()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una regola FallBack specificata alla fine della collezione.
type: docs
weight: 40
url: /it/aspose.slides/fontfallbackrulescollection/add/
---
## FontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) method

Aggiunge una regola FallBack specificata alla fine della collezione.

```cpp
void Aspose::Slides::FontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Regola specificata per l'aggiunta |
## Note

```cpp
auto pres = MakeObject<Presentation>();
//Ottenimento della collezione di regole vuota o preinizializzata da FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Aggiunta di una nuova regola alla collezione
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontFallBackRule](../../ifontfallbackrule/)
* Classe [FontFallBackRulesCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)