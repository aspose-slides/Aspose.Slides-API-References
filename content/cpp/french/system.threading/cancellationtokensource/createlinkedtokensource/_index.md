---
title: CreateLinkedTokenSource()
second_title: Aspose.Slides pour l'API C++
description: Crée une source de jeton liée qui s'annule lorsque l'un des jetons fournis est annulé.
type: docs
weight: 66
url: /fr/system.threading/cancellationtokensource/createlinkedtokensource/
---
## CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken&, const CancellationToken&) méthode

Crée une source de jeton liée qui s'annule lorsque l'un des jetons fournis est annulé.

```cpp
static SharedPtr<CancellationTokenSource> System::Threading::CancellationTokenSource::CreateLinkedTokenSource(const CancellationToken &token1, const CancellationToken &token2)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| token1 | const [CancellationToken](../../cancellationtoken/)\& | Premier jeton d'annulation à surveiller. |
| token2 | const [CancellationToken](../../cancellationtoken/)\& | Deuxième jeton d'annulation à surveiller. |

### Valeur de retour

Nouvelle source de jeton qui sera annulée lorsque l'un des jetons d'entrée est annulé.

## Remarques

La source renvoyée sera immédiatement annulée si l'un des jetons d'entrée est déjà annulé. 

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [CancellationTokenSource](../)
* Classe [CancellationToken](../../cancellationtoken/)
* Espace de noms [System::Threading](../../)
* Bibliothèque [Aspose.Slides](../../../)