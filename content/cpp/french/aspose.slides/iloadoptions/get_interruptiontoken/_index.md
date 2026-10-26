---
title: get_InterruptionToken()
second_title: Référence de l'API Aspose.Slides pour C++
description: Le jeton pour surveiller les demandes d'interruption.
type: docs
weight: 235
url: /fr/aspose.slides/iloadoptions/get_interruptiontoken/
---
## ILoadOptions::get_InterruptionToken() méthode

Le jeton pour surveiller les demandes d'interruption.

```cpp
virtual System::SharedPtr<IInterruptionToken> Aspose::Slides::ILoadOptions::get_InterruptionToken()=0
```

## Remarques

Ce jeton gère la durée de vie complète de l'instance [IPresentation](../../ipresentation/). Toute opération de longue durée, telle que le chargement ou l'enregistrement d'une présentation, sera interrompue en appelant la méthode [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) de [IInterruptionTokenSource](../../iinterruptiontokensource/). 

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInterruptionToken](../../iinterruptiontoken/)
* Classe [ILoadOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)