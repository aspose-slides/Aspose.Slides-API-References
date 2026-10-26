---
title: Join()
second_title: Référence de l'API Aspose.Slides pour C++
description: Joint le thread géré. Effectue une attente illimitée si nécessaire.
type: docs
weight: 196
url: /fr/system.threading/thread/join/
---
## Thread::Join() méthode

Joint le thread géré. Effectue une attente illimitée si nécessaire.

```cpp
void System::Threading::Thread::Join()
```

## Thread::Join(int) méthode

Joint le thread géré. Effectue une attente limitée.

```cpp
bool System::Threading::Thread::Join(int millisecondsTimeout)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | Délai d’attente en millisecondes. |

### Valeur de retour

Vrai si le thread a été joint avec succès, faux si le délai d’attente est dépassé.

## Thread::Join(TimeSpan) méthode

Joint le thread géré. Effectue une attente limitée.

```cpp
bool System::Threading::Thread::Join(TimeSpan timeout)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| timeout | [TimeSpan](../../../system/timespan/) | Un [TimeSpan](../../../system/timespan/) défini à la durée pendant laquelle attendre la terminaison du thread. |

### Valeur de retour

Vrai si le thread a été joint avec succès, faux si le délai d’attente est dépassé.

## Voir aussi

* Classe [Thread](../)
* Classe [TimeSpan](../../../system/timespan/)
* Espace de noms [System::Threading](../../)
* Bibliothèque [Aspose.Slides](../../../)