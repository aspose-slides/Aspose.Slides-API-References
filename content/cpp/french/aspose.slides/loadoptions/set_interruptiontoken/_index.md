---
title: set_InterruptionToken()
second_title: Référence API Aspose.Slides pour C++
description: Le jeton à surveiller pour les demandes d'interruption.
type: docs
weight: 248
url: /fr/aspose.slides/loadoptions/set_interruptiontoken/
---
## LoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) méthode

Le jeton à surveiller pour les demandes d'interruption.

```cpp
void Aspose::Slides::LoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value) override
```

## Remarques

Ce jeton gère toute la durée de vie de l'instance [IPresentation](../../ipresentation/). Toute opération de longue durée, telle que le chargement ou l'enregistrement d'une présentation, sera interrompue en appelant la méthode [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) du [InterruptionTokenSource](../../interruptiontokensource/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInterruptionToken](../../iinterruptiontoken/)
* Classe [LoadOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)