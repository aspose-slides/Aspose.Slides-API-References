---
title: CancellationToken
second_title: Référence de l'API Aspose.Slides pour C++
description: Propage la notification indiquant que les opérations doivent être annulées. Cette classe fournit un mécanisme d'annulation coopérative entre threads, permettant à un thread de notifier les autres qu'une opération doit être annulée.
type: docs
weight: 14
url: /fr/system.threading/cancellationtoken/
---
## CancellationToken classe

Propage la notification indiquant que les opérations doivent être annulées. Cette classe fournit un mécanisme d'annulation coopérative entre threads, permettant à un thread de notifier les autres qu'une opération doit être annulée.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Méthodes

| Method | Description |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | Constructeur par défaut. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | Indique si ce jeton peut être dans l'état annulé. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Indique si une annulation a été demandée pour ce jeton. |
| static [CancellationToken](./) [get_None](./get_none/)() | Retourne une valeur [System::Threading::CancellationToken](./) vide. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | Enregistre un rappel qui sera invoqué lorsqu'une annulation est demandée. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Lance une OperationCanceledException si une annulation a été demandée. |
## Remarques

Un [CancellationToken](./) ne peut être annulé que via son [CancellationTokenSource](../cancellationtokensource/) associé.

## Voir aussi

* Espace de noms [System::Threading](../)
* Bibliothèque [Aspose.Slides](../../)