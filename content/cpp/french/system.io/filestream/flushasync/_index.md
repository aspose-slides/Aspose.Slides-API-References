---
title: FlushAsync()
second_title: Référence API Aspose.Slides pour C++
description: Efface de manière asynchrone tous les tampons de ce flux, provoque l'écriture des données mises en mémoire tampon sur le dispositif sous-jacent et surveille les demandes d'annulation.
type: docs
weight: 157
url: /fr/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) méthode


Efface de manière asynchrone tous les tampons de ce flux, provoque l'écriture de toutes les données mises en mémoire tampon sur le dispositif sous-jacent et surveille les demandes d'annulation.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Le jeton à surveiller pour les demandes d'annulation. |

### Valeur de retour

Une tâche qui représente l'opération de vidage asynchrone.

## Voir aussi

* Typedef [TaskPtr](../../../system/taskptr/)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [FileStream](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)