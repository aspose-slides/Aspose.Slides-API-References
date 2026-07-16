---
title: get_InterruptionToken()
second_title: Référence de l'API Aspose.Slides pour C++
description: Le jeton à surveiller pour les demandes d'interruption.
type: docs
weight: 235
url: /fr/aspose.slides/loadoptions/get_interruptiontoken/
---
## LoadOptions::get_InterruptionToken() méthode

Le jeton à surveiller pour les demandes d'interruption.

```cpp
System::SharedPtr<IInterruptionToken> Aspose::Slides::LoadOptions::get_InterruptionToken() override
```

## Remarques

Ce jeton gère toute la durée de vie de l'instance [IPresentation](../../ipresentation/). Toute opération longue, telle que le chargement ou l'enregistrement d'une présentation, sera interrompue en appelant la méthode [InterruptionTokenSource::Interrupt](../../interruptiontokensource/interrupt/) du [InterruptionTokenSource](../../interruptiontokensource/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInterruptionToken](../../iinterruptiontoken/)
* Classe [LoadOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)