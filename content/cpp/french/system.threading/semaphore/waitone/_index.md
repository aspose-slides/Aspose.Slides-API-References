---
title: WaitOne()
second_title: Référence de l'API Aspose.Slides pour C++
description: Verrouille le sémaphore. Effectue une attente illimitée si nécessaire.
type: docs
weight: 40
url: /fr/system.threading/semaphore/waitone/
---
## Semaphore::WaitOne() méthode

Verrouille le sémaphore. Effectue une attente illimitée si nécessaire.

```cpp
virtual bool System::Threading::Semaphore::WaitOne() override
```

### Valeur de retour

Renvoie toujours true car il ne retourne pas tant que le sémaphore n'est pas verrouillé.

## Semaphore::WaitOne(int) méthode

Verrouille le sémaphore. Effectue une attente si nécessaire.

```cpp
virtual bool System::Threading::Semaphore::WaitOne(int millisecondsTimeout) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| millisecondsTimeout | int | Délai d'attente en millisecondes. |

### Valeur de retour

Renvoie true si le sémaphore a été verrouillé ou false si le délai d'attente est dépassé.

## Voir également

* Classe [Semaphore](../)
* Espace de noms [System::Threading](../../)
* Bibliothèque [Aspose.Slides](../../../)