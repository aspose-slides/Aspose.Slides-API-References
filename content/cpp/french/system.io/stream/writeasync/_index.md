---
title: WriteAsync()
second_title: Référence de l'API Aspose.Slides pour C++
description: Écrit de façon asynchrone une séquence d'octets dans le flux actuel, avance la position actuelle dans ce flux du nombre d'octets écrits et surveille les demandes d'annulation.
type: docs
weight: 66
url: /fr/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) méthode

Écrit de manière asynchrone une séquence d'octets dans le flux actuel, avance la position actuelle dans ce flux du nombre d'octets écrits et surveille les demandes d'annulation.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau contenant les octets à écrire. |
| offset | **int32_t** | Un indice basé sur 0 de l'élément dans **buffer** où commence la sous-plage à écrire. |
| count | **int32_t** | Le nombre d'éléments dans la sous-plage à écrire. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Le jeton à surveiller pour les demandes d'annulation. |

### Valeur de retour

Une tâche qui représente l'opération d'écriture asynchrone.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) méthode

Écrit de manière asynchrone une séquence d'octets dans le flux actuel, avance la position actuelle dans ce flux du nombre d'octets écrits et surveille les demandes d'annulation.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau contenant les octets à écrire. |
| offset | **int32_t** | Un indice basé sur 0 de l'élément dans **buffer** où commence la sous-plage à écrire. |
| count | **int32_t** | Le nombre d'éléments dans la sous-plage à écrire. |

### Valeur de retour

Une tâche qui représente l'opération d'écriture asynchrone.

## Voir aussi

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [Stream](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)