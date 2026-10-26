---
title: ReadAsync()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lit de manière asynchrone une séquence d'octets depuis le flux actuel, avance la position dans le flux du nombre d'octets lus et surveille les demandes d'annulation.
type: docs
weight: 40
url: /fr/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method

Lit de manière asynchrone une séquence d'octets depuis le flux actuel, avance la position dans le flux du nombre d'octets lus et surveille les demandes d'annulation.

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau d'octets dans lequel écrire les octets lus. |
| offset | **int32_t** | Une position à base zéro dans **buffer** où commencer l'écriture. |
| count | **int32_t** | Le nombre d'octets à lire. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Le jeton à surveiller pour les demandes d'annulation. |

### Valeur de retour

Une tâche qui représente l'opération de lecture asynchrone. La valeur du paramètre TResult contient le nombre total d'octets lus dans le tampon. La valeur du résultat peut être inférieure au nombre d'octets demandé si le nombre d'octets actuellement disponible est inférieur au nombre demandé, ou elle peut être 0 (zéro) si la fin du flux a été atteinte.

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Lit de manière asynchrone une séquence d'octets depuis le flux actuel, avance la position dans le flux du nombre d'octets lus et surveille les demandes d'annulation.

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Le tableau d'octets dans lequel écrire les octets lus. |
| offset | **int32_t** | Une position à base zéro dans **buffer** où commencer l'écriture. |
| count | **int32_t** | Le nombre d'octets à lire. |

### Valeur de retour

Une tâche qui représente l'opération de lecture asynchrone. La valeur du paramètre TResult contient le nombre total d'octets lus dans le tampon. La valeur du résultat peut être inférieure au nombre d'octets demandé si le nombre d'octets actuellement disponible est inférieur au nombre demandé, ou elle peut être 0 (zéro) si la fin du flux a été atteinte.

## Voir aussi

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [CancellationToken](../../../system.threading/cancellationtoken/)
* Classe [Stream](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)