---
title: set_InterruptionToken()
second_title: Référence de l'API Aspose.Slides pour C++
description: Le jeton à surveiller pour les demandes d'interruption.
type: docs
weight: 248
url: /fr/aspose.slides/iloadoptions/set_interruptiontoken/
---
## ILoadOptions::set_InterruptionToken(System::SharedPtr\<IInterruptionToken\>) méthode

Le jeton à surveiller pour les demandes d'interruption.

```cpp
virtual void Aspose::Slides::ILoadOptions::set_InterruptionToken(System::SharedPtr<IInterruptionToken> value)=0
```

## Remarques

Ce jeton gère la durée de vie complète de l'instance [IPresentation](../../ipresentation/). Toute opération longue, telle que le chargement ou l'enregistrement de présentation, sera interrompue en appelant la méthode [IInterruptionTokenSource::Interrupt](../../iinterruptiontokensource/interrupt/) de [IInterruptionTokenSource](../../iinterruptiontokensource/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInterruptionToken](../../iinterruptiontoken/)
* Classe [ILoadOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)