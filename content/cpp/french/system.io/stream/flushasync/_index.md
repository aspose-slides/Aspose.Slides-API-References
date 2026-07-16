---
title: FlushAsync()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vide de façon asynchrone tous les tampons de ce flux, entraîne l'écriture des données tamponnées sur le périphérique sous-jacent et surveille les demandes d'annulation.
type: docs
weight: 118
url: /fr/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) méthode

Vide de façon asynchrone tous les tampons de ce flux, entraîne l'écriture des données tamponnées sur le périphérique sous-jacent et surveille les demandes d'annulation.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Le jeton à surveiller pour les demandes d'annulation. |

### Valeur de retour

Une tâche qui représente l'opération d'écriture asynchrone.

## Stream::FlushAsync() méthode

Vide de façon asynchrone tous les tampons de ce flux, entraîne l'écriture des données tamponnées sur le périphérique sous-jacent et surveille les demandes d'annulation.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```

### Valeur de retour

Une tâche qui représente l'opération d'écriture asynchrone.

## Voir aussi

* Typedef [TaskPtr](../../../system/taskptr/)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [Stream](../)
* Espace de noms [System::IO](../../)
* Library [Aspose.Slides](../../../)